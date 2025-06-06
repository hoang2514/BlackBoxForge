# Challenge Ideas

## Basic Challenges
1. **SQL Injection** (unchanged from previous artifact)
2. **XSS** (unchanged)
3. **Port Scanning** (unchanged)
4. **Weak Password** (unchanged)
5. **File Recovery** (unchanged)

## Medium Challenges
1. **Buffer Overflow**
   - Category: Binary Exploitation
   - Description: Exploit a C program to gain shell access.
   - Flag: flag{BOF_SHELL_456}
   - Setup: Docker container with compiled binary.
   - Points: 300
2. **CSRF**
   - Category: Web Exploitation
   - Description: Forge a CSRF attack to change admin password.
   - Flag: flag{CSRF_ADMIN_456}
   - Setup: Node.js app.
   - Points: 250
3. **Packet Analysis**
   - Category: Network Pentest
   - Description: Analyze PCAP file to find flag in HTTP traffic.
   - Flag: flag{PCAP_FLAG_456}
   - Setup: Docker container with PCAP file.
   - Points: 200
4. **Hash Cracking**
   - Category: Cryptography
   - Description: Crack SHA-1 hash to reveal flag.
   - Flag: flag{SHA1_CRACK_456}
   - Setup: Text file with hashed flag.
   - Points: 220
5. **Steganography**
   - Category: Forensics
   - Description: Extract flag hidden in PNG image.
   - Flag: flag{STEGO_PNG_456}
   - Setup: Docker container with image file.
   - Points: 230
   