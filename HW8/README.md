# CyberSecurity-SSILVER-HW#08


Submission: "Its the End of the Assessment as We Know It, and I Feel Fine" 
•	List the steps and commands used to complete the tasks.
•	List any vulnerabilities discovered.
•	List any findings associated to a hacker.
•	Document the mitigation recommendations to protect against the discovered vulnerabilities.
•	Document the OSI layer where the findings were found.


        PHASE-1
•	fping < fping.txt
•	OSI – Network - Layer 3


![OSI Layer](image/HW8-OSI-Layer.png)

![Alive](image/HW8-Alive.png)

![Alive Nano](image/HW8-Alive-Nano.png)

        PHASE-2
•	The cmd ran was nmap -sS 161.35.96.20
•	The transport layer 4 is used for SYN scans
•	Port 22 is open


![ManPage](image/HW8-Task2-SYN-ManPages.png)

![nmap](image/HW8-Task2-nmap-sS.png)


        PHASE-3
•	SSH’d into the server jimi hendrix – rollingstone.com
•	The cmd I ran was ssh jim@161.35.96.20
•	The OSI layer for DNS is Layer 7 (the Application Layer)
•	Reference https://stackoverflow.com/questions/21654632/at-what-layer-in-the-protocol-stack-does-dns-happen#:~:text=In%20OSI%20stack%20terms%2C%20DNS,which%20in%20turn%20use%20IP.


![nslookup](image/HW8-nslookup-unknown.png)

![ssh](image/HW8-Task3-ssh.png)

![nano-etc-hosts](image/HW8-Task3-nano-etc-hosts.png)

        PHASE-4
•	Arp poisoning attack – same ip’s, but different mac addresses
•	OSI Layer 2 = Mac/Arp poisoning


![arp-poisoning](image/HW8-Task4-Arp-Poisioning-Dupe-Mac-Addresses.png)

![nano-packet-capture](image/HW8-Task4-nano-packet-capture.png)

![wireshark-POST](image/HW8-Task4-wireshark-POST-http.png)

![wireshark-arp-poisoning](image/HW8-Task4-Arp-Poisioning.png)



