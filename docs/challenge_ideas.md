# Challenge Ideas

## Basic Challenges
1. **SQL Injection**
   - Category: Web Exploitation
   - Description: Bypass login page using SQL Injection.
   - Flag: flag{BASIC_SQLI_123}
   - Setup: Node.js app with PostgreSQL.
   - Points: 100

2. **XSS**
   - Category: Web Exploitation
   - Description: Inject script to steal flag from admin session.
   - Flag: flag{XSS_COOKIE_123}
   - Setup: Node.js app.
   - Points: 150

3. **Port Scanning**
   - Category: Network Pentest
   - Description: Scan for hidden port to retrieve flag.
   - Flag: flag{PORT_SCAN_123}
   - Setup: Docker container with hidden service.
   - Points: 100

4. **Weak Password**
   - Category: Cryptography
   - Description: Crack MD5 hash to reveal flag.
   - Flag: flag{WEAK_HASH_123}
   - Setup: Text file with hashed flag.
   - Points: 120

5. **File Recovery**
   - Category: Forensics
   - Description: Recover deleted flag file from disk image.
   - Flag: flag{FILE_RECOVERY_123}
   - Setup: Docker container with disk image.
   - Points: 130

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
6. **File Inclusion**
   - Category: Web Exploitation
   - Description: Exploit LFI to read /flag.txt.
   - Flag: flag{LFI_FLAG_456}
   - Setup: Node.js app with vulnerable file inclusion.
   - Points: 270
7. **Protocol Exploitation**
   - Category: Network Pentest
   - Description: Exploit FTP misconfiguration to retrieve flag.
   - Flag: flag{FTP_EXPLOIT_456}
   - Setup: Docker container with FTP server.
   - Points: 260
8. **Format String**
   - Category: Binary Exploitation
   - Description: Exploit format string vulnerability in C program.
   - Flag: flag{FORMAT_STRING_456}
   - Setup: Docker container with compiled binary.
   - Points: 280
9. **Log Analysis**
   - Category: Forensics
   - Description: Find flag in Apache access logs.
   - Flag: flag{LOG_ANALYSIS_456}
   - Setup: Docker container with log files.
   - Points: 240
10. **Linux Privesc**
    - Category: Privilege Escalation
    - Description: Exploit sudo misconfiguration to gain root access.
    - Flag: flag{SUDO_PRIVES_456}
    - Setup: Docker container with misconfigured sudo.
    - Points: 290

## Advanced Challenges
1. **SSRF**
   - Category: Web Exploitation
   - Description: Exploit SSRF to access AWS metadata and retrieve flag.
   - Flag: flag{SSRF_AWS_789}
   - Setup: Node.js app with mock AWS metadata.
   - Points: 500
2. **Heap Exploit**
   - Category: Binary Exploitation
   - Description: Exploit heap vulnerability in C program.
   - Flag: flag{HEAP_EXPLOIT_789}
   - Setup: Docker container with compiled binary.
   - Points: 450
3. **RSA Misconfiguration**
   - Category: Cryptography
   - Description: Exploit weak RSA key to decrypt flag.
   - Flag: flag{RSA_WEAK_789}
   - Setup: Text file with RSA-encrypted flag.
   - Points: 470
4. **Memory Analysis**
   - Category: Forensics
   - Description: Find flag in memory dump.
   - Flag: flag{MEMORY_ANALYSIS_789}
   - Setup: Docker container with memory dump.
   - Points: 460
5. **Kernel Exploit**
   - Category: Privilege Escalation
   - Description: Exploit Linux kernel vulnerability to gain root.
   - Flag: flag{KERNEL_EXPLOIT_789}
   - Setup: Docker container with vulnerable kernel.
   - Points: 480
   