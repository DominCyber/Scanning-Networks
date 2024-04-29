# Scanning Networks (in progress)
##### DISCLAIMER: I DO NOT CONDONE THE USE OF ANY METHODOLOGY OR TECHNIQUE HERE, THIS IS FOR EDUCATIONAL PURPOSES ONLY AND TO DOCUMENT MY PROGRESS. REMEMBER TO CONDUCT OFFICIAL ETHICAL HACKING AND PENETRATION TESTING WITH WRITTEN CONSENT OF ALL PARTY MEMBERS.
## Objective
The EC Council Certified Ethical Hackers Certification labs provide practical cybersecurity skills. This guided project utilizes an attack and victim virtual machine environments to simulate various network scanning in real-time. Cybersecurity professional will become familiar with the methodologies and techinques of ethical hacking on live hosts.

### Skills Learned
-Recognize and discover:
<p>--Open ports on live hosts</p> 
<p>--OS fingerprinting on live hosts</p> 
<p>--services running on live hosts</p> 
<p>-NetScanTools Pro GUI port and ping scans</p> 
<p>-Nmap CLI commands and switches for scanning</p> 
<p>--ARP ping scan</p> 
<p>--UDP ping scan</p> 
<p>--ICMP ping scan</p> 
<p>--TCP ping scan</p> 
<p>--IP ping scan</p> 
<p>--IDS/Firewall evasion techniques for scanning</p> 
<p>-Zenmap GUI commands and switches for scanning</p> 
<p>-WireShark GUI packet artifacts</p> 
<p>-Hping3 CLI commands and switchesfor scanning</p> 
<p>--Custom packets to scan beyond IDS/Firewalls</p> 
<p>-Metasploit CLI commands and switches for scanning</p> 

### Tools Used
-Laptop
<p>-Windows 11 hypervisor</p>
<p>-Parrot Security (Linux) hypervisor</p>
<p>-NetScanTools Pro GUI</p>
<p>-Nmap CLI</p>
<p>-Zenmap GUI</p>
<p>-WireShark GUI</p>
<p>-Hping3 CLI</p>
<p>-Metasploit CLI</p>
<p>-The EC Council Certified Ethical Hackers Certification</p>

### Steps
<img src="https://i.imgur.com/WWWvy5M.jpg" style="width: 65%;" alt="1">
<p><i>Ref 1: Examples of ARP and UDP ping scans while disabling port scans</i></p>
<img src="https://i.imgur.com/fH5VAwt.jpg " style="width: 65%;" alt="1">
<p><i>Ref 2: Example of an ICMP ping scan while disabling port scans</i></p>
<img src="https://i.imgur.com/HarVGtC.jpg" style="width: 65%;" alt="1">
<p><i>Ref 3: Example of ICMP timestamp, ICMP address mask, and TCP SYN ping scans while disabling port scans</i></p>
<img src="https://i.imgur.com/8nUJpJt.jpg" style="width: 65%;" alt="1">
<p><i>Ref 4: Example of TCP ACK and IP protocol ping scans while disabling port scans</i></p>
<img src="https://i.imgur.com/NwGGXBH.jpg" style="width: 65%;" alt="1">
<p><i>Ref 5: NetScanTools Pro GUI IP range ping scanner results host discoveries</i></p>
<img src="https://i.imgur.com/moEPRmE.jpg" style="width: 65%;" alt="1">
<p><i>Ref 6: NetScanTools Pro GUI IP range port scanner results open port discoveries</i></p>

<img src="https://i.imgur.com/yIsOmC2.jpg" style="width: 65%;" alt="1">
<p><i>Ref : TCP port scan</i></p>
<img src="https://i.imgur.com/MYSPD6b.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Zenmap Ports/Host table selected, emphasis on services on each port</i></p>
<img src="https://i.imgur.com/NDn7yJR.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Zenmap Topology selected</i></p>
<img src="https://i.imgur.com/iw6yqON.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Stealth/half open scan retrieves information before full TCP handshake is established, breaking it beforehand</i></p>
<img src="https://i.imgur.com/iCf8id3.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Xmas attack against a target results in a RST flag return (Not Shown:1000 closed TCP ports (reset))</i></p>
<img src="https://i.imgur.com/l5IIZ8R.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Maimon attack FIN/ACK probe against a target results in lts in a RST flag return (Not Shown:1000 closed TCP ports (reset))</i>></p>
<img src="https://i.imgur.com/o2Q2B8g.jpg" style="width: 65%;" alt="1">
<p><i>Ref : ACK flag probe return RST flags, which would mean target ports are unfiltered (Not Shown:1000 unfiltered TCP ports(reset))</i></p>
<img src="https://i.imgur.com/WPVn5nX.jpg" style="width: 65%;" alt="1">
<p><i>Ref : UDP ports scan on a target, resulting in most UDP ports either filtered or closed, and five open showing their services on those ports </i></p>
<img src="https://i.imgur.com/w8MGZdY.jpg" style="width: 45%;" alt="1">
<p><i>Ref : Null scan with aggressive switches and timing templates selected against a server, resulting in valuable artifacts</i></p>
<img src="https://i.imgur.com/GFMPm4M.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Version scan example</i></p>
<img src="https://i.imgur.com/RZX8WPg.jpg" style="width: 65%;" alt="1">
<p><i>Ref : Zenmap host details from an aggressive scan and IP with a wild card displaying host artifact</i></p>
<img src=" " style="width: 65%;" alt="1">
<p><i>Ref : </i></p>
<img src=" " style="width: 65%;" alt="1">
<p><i>Ref : </i></p>
<img src=" " style="width: 65%;" alt="1">
<p><i>Ref : </i></p>
