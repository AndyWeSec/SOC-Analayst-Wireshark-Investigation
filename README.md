# SOC-Analayst-Wireshark-Investigation
Investigated a phishing-to-ransomware compromise using the TryHackMe Carnage PCAP challenge. Traced malicious ZIP downloads, analyzed HTTP/DNS traffic, and mapped two Cobalt Strike C2 servers via VirusTotal. Analyzed post-infection beaconing and SMTP data exfiltration to build complete incident timelines.

### Finding the date and time for the first HTTP connection to the malicious IP
<img width="796" height="660" alt="Screenshot 2026-06-12 at 06 48 20" src="https://github.com/user-attachments/assets/4576a51c-a422-4b4f-9a70-7eca7b8f7de6" />
<img width="834" height="696" alt="Screenshot 2026-06-12 at 06 53 52" src="https://github.com/user-attachments/assets/4ef8ef8c-62b4-427b-ba6d-0e273d724d19" />
<img width="912" height="726" alt="Screenshot 2026-06-12 at 07 00 13" src="https://github.com/user-attachments/assets/93aa2e99-e5e1-4448-9a93-948148494bf3" />

### Finding the name of the zip file that was downloaded
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 34 41" src="https://github.com/user-attachments/assets/09a66ae2-264d-4ac5-8001-be467573aa44" />

### Finding the domain hosting the malicious zip file
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 37 23" src="https://github.com/user-attachments/assets/1f77bc93-f21a-48fb-a1a2-28d6f219b3ea" />

### Finding the name of the file in the zip file, without downloading the file
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 40 51" src="https://github.com/user-attachments/assets/8b850376-782e-462a-b8a8-b63968d8aa0a" />
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 41 03" src="https://github.com/user-attachments/assets/09187c1b-a25b-4087-9271-508546a7571d" />
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 41 11" src="https://github.com/user-attachments/assets/df8331d0-78b8-4b66-bf05-8f53f2d85acf" />
<img width="849" height="717" alt="Screenshot 2026-06-12 at 15 41 35" src="https://github.com/user-attachments/assets/5e3a7c89-87fe-4042-9f8f-47880cf3f2ce" />

