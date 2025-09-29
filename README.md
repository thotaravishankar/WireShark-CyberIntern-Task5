# WireShark-CyberIntern-Task5

# Task 5: Capture and Analyze Network Traffic Using Wireshark

##  Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

##  Tools Used
- Wireshark 
- Operating System: Windows 11

##  Steps Performed
1. Installed Wireshark.
2. Started packet capture on active network interface.
3. Generated traffic by browsing websites and using ping command.
<img width="1475" height="652" alt="Screenshot 2025-09-29 131746" src="https://github.com/user-attachments/assets/65e11b41-4adb-4f09-b25c-d9e6a7de59b5" />

4. Stopped capture after 1 minute.
5. Applied filters (HTTP, DNS, TCP, etc.).
6. Identified multiple protocols in the captured data.
7. Exported capture as `.pcap` file.


-------->Screenshot of ICMP packets from source(my pc) to destination google.com server address by doing ping operation in command prompt
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/823b6e7f-df4f-438f-83ac-0beadd511d98" />

----------> Screenshot of HTTP Protocol packets from Source(my pc) to destination facebook.com by browsig in chrome
<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/313bac03-1181-4db7-8660-d4739cd4f315" />

-------->Screenshot of DNS Protocol Packets by doing nslookup commmand operation in command prompt. 
<img width="1479" height="553" alt="Screenshot 2025-09-29 133646" src="https://github.com/user-attachments/assets/c5df6685-46b2-4490-9ef3-2688662aa45e" />

<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/9b1029bc-0f0b-4bd3-82d1-871585de1c04" />

--------->Screenshot of TCP Protocol packets from source(my pc) to destiantion facebook.com by browsing. By this operation TCP protocol will sent tcp packets to destination and source to complete three way handShake rule to establish a connection between them
<img width="1919" height="390" alt="Screenshot 2025-09-29 134015" src="https://github.com/user-attachments/assets/4dd28e71-0a76-4fe2-ae01-76625993bc7f" />

##  Protocols Identified
- **HTTP** – Used for web communication (port 80/443).
- **DNS** – Used for domain name resolution (port 53).
- **TCP** – Connection-oriented traffic management.
- **ICMP** – Used for ping requests .
  


##  Summary of Findings
- Successfully captured and analyzed live traffic.
- Observed communication across multiple protocols.
- Gained hands-on experience in using Wireshark for traffic analysis.


