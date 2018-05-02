CodePath University's Web Security

# Project 9 - Honeypot

Time spent: **15** hours spent in total

- [x]	Milestone 0: To the Cloud!

- [x]	Milestone 1: Create MHN Admin VM

- [x] Milestone 2: Install the MHN Admin Application

- [x] Milestone 3: Create a MHN Honeypot VM

- [x] Milestone 4: Install the Honeypot Application

- [x] Milestone 5: Attack!

### Demo on creating a MHN Honeypot
![Alt Text](honeypot-demo.gif)


### Which Honeypot(s) you deployed
1. dionaea with HTTP
2. snort
3. amun
4. cowrie

![Alt Text](honeypot-overview.gif)
  
### Any issues you encountered
The hardest part of this entire lab is setting up the honeypots in GCP. Took up most of the time...

### Attack Summary

**number of attacks:** 11,915

**Top 5 Attacker IPs:** 
1. 118.89.239.33 (4,063 attacks)
2. 123.207.146.91 (3,962 attacks)
3. 46.166.142.231 (336 attacks)
4. 50.232.230.82 (310 attacks)
5. 175.101.84.42 (114 attacks)

**Top 5 Attacked Ports:**
1. 80 (8,191 times)
2. 445 (1,413 times)
3. 5060 (479 times)
4. 8080 (174 times)
5. 3306 (132 times)

### Any unresolved questions raised by the data collected
None as of right now.

### References

[MHN](https://github.com/threatstream/mhn#installing-server-tested-ubuntu-12043-x86_64-and-centos-67 "MHN")

[gcp mhn instructions](https://github.com/RedolentSun/gcloud-instructions-for-mhn)
