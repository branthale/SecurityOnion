# Security Onion random notes

## Enable password extraction
/opt/bro/share/bro/site/local.bro
 redef HTTP::default_capture_password = T;
 redef FTP::default_capture_password = T;

## Kill all the perl processes
kill -9 `ps -ef | grep perl | grep -v grep | awk '{print $2}'`

## Delete all the extracted bro files fast 
perl -e 'for(</nsm/bro/extracted/*.exe>){unlink}'

## Backup all of your SGUIL users 
sudo mysqldump securityonion_db user_info -uroot > userbackup.sql

## Add e-mail address to SGUIL users
sudo mysql --defaults-file=/etc/mysql/debian.cnf -Dsecurityonion_db -e 'update user_info SET email ="haleb@branthale.com" where uid = 2;'

