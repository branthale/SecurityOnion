# Notes from the Security Onion Conference 2018 Augusta GA

## Save Time with Modern Search Techniques 

Searching a billion logs a minute

bluesmote.com
CERT INsider Threat tools

markjx/search2018
https://github.com/markjx/search2018   [MarkJX (https://github.com/markjx/search2018)]
Mark Jenmougin

GNU Parallel
   parallel -u lz4cat {} \| grep -f /var/opt/ldata/badurls | wc -l
   parallel -j 110% -u lz4cat \| grep -F /var/opt/ldata/badurls | wc -l
    much faster no regex
    
New commands 

   squishycat     decompress all the things
   grepwide       simplified parrallel GREP    

## Blue, Red, Purple, White : Which team are you?

five students one trainer 
    Practice Incident Response
    moloc 
    so-import-pcap
    www.bt3.no
    https://www.encripto.no/forskning/whitepapers/BT3_User_guide.pdf
    opensoc.io
 
https://github.com/sm-biz/paloalto-elasticstack-viz/wiki
WES reindex script

## GCC Overview and Mission

Todd Gay
Govt, Industry, and schools - colloboration 
   GBI, Clubhouse, students, Augusta Univ, Augusta Tech, Parsons, DOD, Cafe,  



## PCAPS Ahoy! Commodity Malware Infections on Windows Hosts

keep the anyalsts happy and sharp
     Red Team or pentesting
     Forsensics
     Hunting / Active Defense
Looking at Commodity Malware
     Sanitizing pcap  - TraceWrangler
     hex editor BLESS
     Customizing Wireshark - Changing Your Column Display Brad Duncan Unit 42
     
Trickbot  2018-10-16-Trickbot.pcap  
Emotet/Freedo 

 [] Lunch
 
 ## Integrating Osquery into Security Onion
 osquery  (facebook)
     Treat system like a relational DB
     cross platform
     
     osquery.io/schema
     
     github.com/bro/bro-osquery
     
     Wuzuh Integration
     learnosquery.com
     defensivedepth.com
    
## Getting the Most Out of Freq and Domain_Stats

     Mark Baggett
     
     https://tinyurl.com/sec-onion-2018-markbaggett
     
     SEC573 auto infose with python
     
     /opt/metasploit-freamworkd$ grep -Ri "mark baggett"
     
     Look at whois creation date 
     
     github.com/markbaggett/domain_stats
     
## Intro to Data Analysis with Security Onion
David Bianco

@DavidJBianco

jupiter - notebook

import pandas as pd

import numpy as np

   Series
   
   Dataframe

from huntlib.elastic import ElasticDF

github.com/target/huntlib

stack counting - 1st rule of threat hunting club

Time series anaylsis 

