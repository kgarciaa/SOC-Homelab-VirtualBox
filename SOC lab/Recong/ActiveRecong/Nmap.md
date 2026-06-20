While utilizing Nmap on the Kali machine i did some reconnaissance probing to arrogate Ubuntu logs on Splunk 
The attachment below will showcase the command used: 
![[Pasted image 20260619224909.png]]I used the nmap -sV  192.168.1.10 command to probe open ports and reveal their services, like software on open ports and their version. 
In addition, the command nmap -A 192.168.1.10 could be used to reveal OS, service version and other host information.  