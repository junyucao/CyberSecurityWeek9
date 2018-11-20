# CyberSecurityWeek9

## Which Honeypot(s) you deployed
I deployed a MHN Honeypot Dionaea through the Google Cloud Platform(GCP).

## Any issues you encountered
Most instructions are give accordingly to GCP, however, most students may have expired free trial. A work around of this was setting a GCP free trail on a different gmail and different computer. Then use that acccount to log into personal device. 

The installation of sudo ./install.sh in milestone 2 throws error due to certain non-existing repository. Had to instead sudo git clone https://github.com/threatstream/mhn.git instead of https://github.com/RedolentSun/mhn.git. 

Afterwards the browser is not able to login to admin console, had to check allow http in its settings to fix this.

## A summary of the data collected: number of attacks, number of malware samples, etc.
Deployed the honeypot VM for 12 hours and accumalated 2,411 attacks.
Top attacked ports 
1. 8088: 710 times
2. 5060: 265 times
3. 23: 200 times
4. 445: 94 times
5. 81: 46 times

Most attacks are from IP in the United States, France, and England
No malware samples were detected

## Any unresolved questions raised by the data collected
None
