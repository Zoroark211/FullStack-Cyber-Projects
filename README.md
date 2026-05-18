# FullStack-Cyber-Projects
This is a Repository holding my unit projects for FullStack Academy Cyberseurity projects

Unit 5 project: Digital Forensics and Steganography: Recovering Hidden Data from a JPG Image.
  Problem Statement: 
  Simulate a scenario by deleting the file and making it inaccessible. Utilize FTK (Forensic Toolkit) to recover the deleted       file from the disk image and extract the hidden text from the recovered JPG. This project highlights data-hiding methods and     the forensic recovery process.
  
  Objective:
  To demonstrate the process of embedding text into a JPG image using steganography techniques and storing it on a 2-disk system   to simulate real-world data storage
  
  Steps to Perform:
  - Create a JPG image and hide text using steganography
  - Download and prepare the data to be tested
  - Download Access data FTK Imager
  - Hide text in the image using Steganography
  - Store the image on a 2GB Disk in NTFS
  - Recover the deleted file using FTK

Unit 6 project: Uncovering Digital Information for Security Analysis Using Footprinting, Reconnaissance, and Scanning

  Problem Statement: 
  A financial institution observes abnormal access attempts, prompting a cybersecurity team to conduct reconnaissance using        tools like Google Dorks, Whois Lookup, and NsLookup.
  Network scans with Nmap and Metasploit reveal critical vulnerabilities, including open ports and outdated software.
  The team proposes mitigation measures to strengthen defenses before a potential attack can occur.

  Objective:
  To perform footprinting, reconnaissance, and network scanning to identify system vulnerabilities
  Learners will use OSINT tools, detect live hosts, analyze findings, and recommend security measures, gaining hands-on            experience in ethical hacking and cybersecurity defense

  Steps to Perform:
  - Gather publicly available information using Google Dorks, Whois Lookup and NsLookup to identify exposed sensitive data,           domain details, and DNS records
  - Identify domain names associated with each IP address to uncover additional target systems
  - Retrieve point-of-contact (POC) details and ownership information from Whois queries
  - Compile collected Whois data into a structured report for reference
  - Use enumeration tools to identify associated subdomains and their corresponding IP addresses
  - Perform a network scan to detect open ports, services, and vulnerabilities for further security assessment

Unit 7 project: Exploiting Android with Metasploit

  Problem Statement: 
  Smartphones are targeted by attackers who exploit Android vulnerabilities to steal data and monitor users.
  A security team uses Metasploit to deploy a malicious APK and assess threats posed by untrusted apps.
  This analysis reveals how remote access can compromise sensitive data and device functionality.
  
  Objective:
  To use Metasploit for generating and deploying a malicious APK, exploiting an Android device, and analyzing the security risks   involved.
  
  Steps to Perform:
  - Install and configure an Android virtual machine using VirtualBox with appropriate network settings.
  - Use Metasploit to create an APK with a reverse shell payload and deliver it to the target device via an Apache2 web server         or direct transfer.
  - Leverage Metasploit’s multi-handler to initiate and maintain a reverse shell connection with the compromised Android device.
  - Assess vulnerabilities exploited during the attack and apply security measures such as app permissions control, network            monitoring, and malware detection.
