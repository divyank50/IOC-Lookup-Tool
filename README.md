# IOC-Lookup-Tool

- The Cyber Threat Intel Lookup is a Chrome Extension designed to help cybersecurity professionals, threat analysts, and researchers quickly investigate Indicators of Compromise (IOCs). The tool allows users to check file hashes, IP addresses, and URLs against three major threat intelligence databases:

  MalwareBazaar (for malware sample hashes)
  ThreatFox (for IPs and domains associated with cyber threats)
  URLHaus (for malicious URL analysis)
  VirusTotal (for Hash and IP Analysis)
- By leveraging these open-source threat intelligence APIs, this extension helps users detect, analyze, and respond to potential security threats in real-time—directly from their browser. 
- Additional Threat Intel integreations are work in progress.


**The examples used below are real IOC's, please don't click or interact with them, if you do I won't be responsible for anything.**
**Tool Usage:**
1. _ThreatFox_
- IPAddress:Port [Example: 54.208{.}144.249:443]
- URL/Domain [Example: www{.}deskschoolpro.com OR albummgronakw{.}shop]
<img width="1333" alt="Screenshot 2025-02-12 at 10 10 16 PM" src="https://github.com/user-attachments/assets/c0014bc7-acbb-4b65-bd34-13d381973a65" />


2. _MalwareBazaar_
- SHA 256 Hash [Example: 73bd5e94055c1896a006261d1507d60bd20654f073e06fde9db6a337865bc7f9]
- MD5 Hash [Example: cfd49ff803bee148321ed6d276e15546]
<img width="1340" alt="Screenshot 2025-02-12 at 10 09 40 PM" src="https://github.com/user-attachments/assets/4a4f7e7c-1383-4420-9578-10ff533507ef" />


3. _URLHaus_
- URL [Example: http{:}//180.115.79.215:43080/bin.sh]
<img width="1341" alt="Screenshot 2025-02-12 at 10 07 16 PM" src="https://github.com/user-attachments/assets/607cdb85-1afc-4897-8a6f-1c67a19bb058" />

4. _VirusTotal_
   <img width="1286" alt="Screenshot 2025-02-17 at 2 55 59 PM" src="https://github.com/user-attachments/assets/154ca047-ee10-4316-bf80-92cf3e99c387" />
   <img width="1236" alt="Screenshot 2025-02-17 at 2 59 39 PM" src="https://github.com/user-attachments/assets/1807ef48-7849-49a9-9a38-9281abfde4c5" />



**TOOL USAGE INFO:**
To add this extension into your browser, perform the following:
- [Download the Folder] ([Cyber Threat Intel Lookup.zip](https://github.com/divyank50/IOC-Lookup-Tool/blob/main/Cyber%20Threat%20Intel%20Lookup.zip))
- Extract the folder
- On line 148 and 200 in background.js file, add the VT API KEY and save the file
- Go to chrome://extensions/
- Enable "Developer Mode" on the Top Right
- Click on "Load Unpacked" button
- Select the folder that you download
- Now you should see the extension called "Cyber Threat Intel Lookup", make sure its enabled
- Now you can pin the extension for ease of use

