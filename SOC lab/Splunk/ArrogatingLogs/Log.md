Log Failed SSH logon attempts on Splunk.
Note: Failed SSH authentication attempts were successfully detected and ingested into Splunk. Logs on Splunk showed the pfSense LAN interface rather than the Kali host IP, demonstrating how NAT configuration can affect how logs are displayed on Splunk
Defensive solution: Blacklisting source IP 
![[Pasted image 20260619224308.png|697]]