# Bsides Augusta 2018

## Keynote 

### Github Sites
 
 trustedsec trevorc2
 
 losbas
 
 api0cradle 

### Red Team stuffs

Mitre Caldera

Atomic Red Team

## Anatomy of Cloud Hack              Track 3 10:00

Use one cloud and learn it well

analytics 

Dwell - is 48hours not 90days

Red team - enumeration is easy and all environments are similar

  Snapshots are a thing to look for / easy to steal 
  
  S3 bucket scanning - dns query on predictable names
  
  Bitcoin mining in Cloud - instance limits!
  
  Alert on  any/any acl    public bucket      instances invoking user creds instead of instance roles     boxes boote outside of standards templates
  
  New user agents or IP's have downloaded objects
  
  v=YZ058hmLuv0    youtube    Lambda hack 
  
  application letters  - Qubes OS 
  
Fight with visibility 
  Mtrends 
  Azure network watcher flows 
  Monitor SMB on direct access link
  
  Azure -  Tenant activity logs, activity logs OMS, Network watcher flow logs, Securiy Center
  Azure changes so fast how to keep up 
  
  pcaps - port 53 get dns 


## Breaking into Banks Like a Boss    Track 3 11:15 

Brice Self    @RenditionSec    @B_Selfless

 Cover for Action and Status 
 
 Support Items - Disguise
 
 Acting skills 

## Skill Sharpening @ Cyberrange      Track 2 12:30

Don Murdoch

BAS (Gartner) Breach and Adversary Simulations

KSA
 NICE /NICCS INRE and CDA
 
 Need intial KSA1 assessment, entry points, and progression model
 Charge code  est time 23-143 hours of prep for every hour of event 
 Use reusabele resources 
 Record keeping - did we accomplish the goals    CTFB
 Root cause analysis - get them to do this 
 
 e-mail delivery, root names servers, forwarders (AWS for e-mail?)
 
 Autuloab, automatedlab, boxstarter
  LAN/WAN GNS3, Cisco VIRL
 
 DetectionLab
  Multistage ext
  AD, DNS, event forwarding, 
  
 Toolsets 
  Apt simulator, Atomic Red Team, BT3, NSA unfetter
  
  SILK, BHIS RITA
  QRADAR
  Relkci - whitenoiselist 
  log MD
  OPENSOC.io
  Sec Onion 
  
 PenTestIT FOSS Compared - chart
 
 APT simulator - batch tool     NextronSystems/APTSimulator
 
 www.bt3.io   low cost 
 
 Atomic Red Team
  Import-Module 
  
 Breaking Point by IXIA
 
 Attack IQ   
 
 Scythe - adsim
 
Range ISMs
 Agents - do not pivot, do not adjust, go after one thing domain admin, don't read e-mail
 Tools that use agent aren't that real
 4688 Detail tracking / don't teach them something that they can't do
 
 

## The Sound of Evil                  Track 2 1:30

Siri waning 
Alexa is winnning 
Google dot 

github.com/worldviel/dejavu

Alexa is andriod, side channel commands, over privledged, data capture/exfil, teaching users bad habits



## Movement After Initial Compromise  Track 3 2:15

SleepZ3R0

sixgen  ACO

powerup   DLL hijacking 

winrm

remote registry 
   REG ADD 
   
 DCOM  
 
 Responder    LLMNR NBT-NS   
 runfinger.py -i 192.168.1.1
 
 multi-relay    htt,webdav
 
 port forwarding     ssh -l     portfwd add -l 3389,  plink port forwarding
 
 kali   proxychaings.conf 
 proxychains nmap -p 22 192.168.1.1 
 
 Bloodhood 
 
 neo4j console 
 
 

## Comparing apples to Apple          Track 1 3:15

macOS three things :   Code Signing Entitlements Sandboxing 

powershell             applescript, bash, python, ruby, perl, php, and powershell ?

Mitre ATT&K framework 

net.exe       dscl/dscachetutil
misinfo32     system_profiler
nmap.exe      stroke
doskey        .bash_history
dll hijacking  Dylib Hijacking   

Mac  eggshell tool 

look for osascript    in logs 

mimikatz       Keychain access 
security find-internet-password -gs 
security dump-keychain -d login.keychaing > keychain.txt

/Library/Preferences/login.keychain-db    keychain file
psexec       applescript

Persistence
/Library/StartupItems
LaunchDaemons
LaunchAgents
cron jobs/launchct


    

## Objectively Measuring Hunt Value   Track 1 3:45

Justin Kohler ICEBERG / Gigamon

theford wall Patrick Perry

Threat Hunting - no defined standad, retrospectivce detection, human directed, begins with a question, pivot 
 
Problems
Why
how - hypothesis formation, example
webinars

How do we measure success?
 metrics 
 how do you record sucess 
 
Basics 
 Terms
   Hunting Hypothesis  - Mitre ATT&Ck tactics and techniques (SpecterOPS)
   Hunting Activity      Non-malicous,  Nothing, malicous
   Hunting Outcome       Incident created, detection/analytic created, vuln identified, logging gap, insecure practice
   
   Ref  NIST CSF   
   
   
Solution

Confluence JIRA    logging gaps, dets created, active hunts,
   
github.com/pjbperry/Presentations

Raffle 252732-741
