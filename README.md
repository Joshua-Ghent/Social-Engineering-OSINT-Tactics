# Social Engineering & OSINT Tactics

## Objective

The objective of this lab is to understand how social engineering tactics can be used to conduct targeted attacks through open-source intelligence (OSINT), deception, and psychological manipulation. Students explored how to gather intelligence, design pretext attacks, and identify countermeasures, while also investigating vulnerabilities through simulated email phishing, data leaks, and blog mining.

### Skills Learned

-Conducting reconnaissance using WHOIS data, blogs, and employee profiles.

- Gathering intelligence through online platforms like GetConnected and LinkedIn.

- Identifying software version exposure via blog entries.

- Creating and analyzing fake job advertisements for reverse social engineering.

- Executing phishing-style attacks through spoofed emails and tracking responses.

- Performing Nmap scans and source code inspections to locate hidden files or data leaks.

- Understanding how seemingly innocuous information can lead to real-world compromise.
### Tools Used

- Browser-based OSINT tools – to view employee profiles, WHOIS records, and blogs.

- Thunderbird Email Client – for simulating spear-phishing email responses.

- Nmap – for enumerating open ports and analyzing network exposure.

- Web Dev Tools / Source Inspector – to find hidden elements or sensitive file references.

- Excel Viewer – to analyze spreadsheet content for clues and hidden data.

## Steps
Ref 1: WHOIS Lookup for Global Enterprises
Screenshot showing domain registration data, creation/expiration dates, and registry ID from whois.pdf.
![image](https://github.com/user-attachments/assets/ebf9f131-767d-4d5b-9323-3bb0ee069b78)


Ref 2: LouAnne's GetConnected Profile
Screenshot from her profile.pdf showing details used to identify her as a phishing target.
![image](https://github.com/user-attachments/assets/10a5e54d-dfa1-45d6-84ac-fed337fa0a96)


Ref 3: Blog Entry 1 & 2 (Recon on Firewall/Email Server)
Screenshots from blog1.pdf and blog2.pdf, containing software details of Global Enterprises.
![image](https://github.com/user-attachments/assets/69015e5c-9166-455e-afb7-307b36207d25)


Ref 4: Current Firewall Software Version
Research showed pfSense version 6.2.3 — used to plan potential exploits.
![image](https://github.com/user-attachments/assets/cb6ea0cd-83ec-4375-861b-fde9526fdecc)


Ref 5: Fake Job Advertisement
Screenshot of a crafted job ad from ad.pdf, targeting LouAnne for a reverse social engineering attack.
![image](https://github.com/user-attachments/assets/00f47fa4-40bc-4395-8c82-ce41cc9a7eb4)


Ref 6: Corporation Techs Services and Officers
Screenshots of consulting services and executive team on https://www.corporationtechs.com.
![image](https://github.com/user-attachments/assets/143bbffa-82c0-48c6-b641-f9609a440fc9)


Ref 7: LinkedIn Profiles Summary
Bullet-point answers based on browsing LinkedIn profiles of Andrew Simmons, Mike Hutchins, and Dee Dasher.
![image](https://github.com/user-attachments/assets/8bb7ab84-4c10-41a6-af73-4382364f6728)


Ref 8: Spoofed Email and Response Page
Screenshot of the phishing email content via Thunderbird, and the resulting web page after clicking the link.
![image](https://github.com/user-attachments/assets/03e90e2f-ec47-4069-9a02-beb043e8cb7a)


Ref 9: Nmap Scan Results on Web Server
Screenshot showing discovered open ports and possibly exposed directories.
![image](https://github.com/user-attachments/assets/4a03087d-50ab-4bd4-a1b4-298fc2d4d0e7)


Ref 10: Hidden Script Triggering “pricecheat” PDF
Screenshot of the browser’s inspector revealing the hidden shortcut and script associated with the leaked document.
![image](https://github.com/user-attachments/assets/5675af1f-4989-4a34-80be-9568bbdec730)


Ref 11: Data Leak Access Confirmation
Screenshot showing successful retrieval of the hidden pricecheat.pdf file via keyboard trigger on the Corporation Techs homepage.
![image](https://github.com/user-attachments/assets/f69ba6c8-f8fe-4ec7-96c9-fa1cb73e607f)
