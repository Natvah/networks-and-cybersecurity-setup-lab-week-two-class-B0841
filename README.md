# networks-and-cybersecurity-setup-lab-week-two-class-B0841
Documentation of my Week 2 Networkwalks Cybersecurity Internship practical lab, focusing on Footprinting and Reconnaissance using six Kali Linux tools: WHOIS, WhatWeb, NSLookup, CURL, WAFW00F, and DNSRecon. Includes practical commands, results, screenshots, and key lessons learned.

# Networkwalks Cybersecurity Internship – Week 2

## Footprinting and Reconnaissance Using Multiple Kali Linux Tools

### 1. Introduction

This repository documents my practical work for Week 2 of the Networkwalks Cybersecurity Internship.

The lab focused on Footprinting and Reconnaissance, which involves gathering and analysing publicly available information about a target domain using various Kali Linux tools.

### 2. Lab Objectives

- Understand the importance of footprinting and reconnaissance in ethical hacking.
- Identify publicly available domain registration information.
- Fingerprint website technologies.
- Resolve domain names into IP addresses.
- Examine HTTP response headers.
- Identify the presence of a Web Application Firewall.
- Examine DNS records.

### 3. Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| NSLookup | DNS resolution |
| CURL | HTTP response headers |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS enumeration |

### 4. Practical Tasks and Evidence

#### Task 1: WHOIS – Domain Registration

**Objective:** Retrieve publicly available domain registration information.

**Command used:**
```bash
whois networkwalks.com
```

**Key learning:** Understanding domain registration details, registrars and name servers.

**Screenshot:**

![Task 1 - WHOIS Screenshot](Task-1-WHOIS/Task1-WHOIS.png)

**Output file:** `task1-whois.txt`

---

#### Task 2: WhatWeb – Website Fingerprinting

**Objective:** Identify technologies used by the target website.

**Command used:**
```bash
whatweb networkwalks.com
```

**Key learning:** Understanding how website technologies and frameworks can be identified.

**Screenshot:**

![Task 2 - WhatWeb Screenshot](Task-2-WhatWeb/Task2-WhatWeb.png)

**Output file:** `task2-whatweb.txt`

---

#### Task 3: NSLookup – DNS Resolution

**Objective:** Resolve the target domain name to its associated IP address.

**Command used:**
```bash
nslookup networkwalks.com
```

**Key learning:** Understanding DNS resolution and IP address identification.

**Screenshot:**

![Task 3 - NSLookup Screenshot](Task-3-NSLookup/Task3-NSLookup.png)

**Output file:** `task3-nslookup.txt`

---

#### Task 4: CURL – HTTP Response Headers

**Objective:** Examine HTTP response headers returned by the website.

**Command used:**
```bash
curl -I https://networkwalks.com
```

**Key learning:** Understanding HTTP response codes, server information and response headers.

**Screenshot:**

![Task 4 - CURL Screenshot](Task-4-CURL/Task4-CURL.png)

**Output file:** `task4-curl.txt`

---

#### Task 5: WAFW00F – Firewall Detection

**Objective:** Check whether a Web Application Firewall protects the target website.

**Command used:**
```bash
wafw00f networkwalks.com
```

**Key learning:** Understanding the role of Web Application Firewalls in web application security.

**Screenshot:**

![Task 5 - WAFW00F Screenshot](Task-5-WAFW00F/Task5-WAFW00F.png)

**Output file:** `task5-wafw00f.txt`

---

#### Task 6: DNSRecon – DNS Enumeration

**Objective:** Examine publicly available DNS records associated with the target domain.

**Command used:**
```bash
dnsrecon -d networkwalks.com
```

**Key learning:** Understanding DNS records, including NS, MX, TXT and SRV records.

**Screenshot:**

![Task 6 - DNSRecon Screenshot](Task-6-DNSRecon/Task6-DNSRecon.png)

**Output file:** `task6-dnsrecon.txt`

---

### 5. Skills Developed

Through this practical exercise, I developed experience in:

- Kali Linux terminal operations.
- Domain information gathering.
- Website technology fingerprinting.
- DNS investigation.
- HTTP header analysis.
- Web Application Firewall identification.
- Technical documentation and evidence collection.

### 6. Lessons Learned

This lab demonstrated the importance of reconnaissance in cybersecurity. I learned that different tools provide different perspectives of a target's digital footprint and that gathering and analysing this information helps security professionals understand an organisation's publicly exposed infrastructure.

### 7. Conclusion

Week 2 provided valuable hands-on experience with six Kali Linux reconnaissance tools. The practical activities strengthened my understanding of footprinting, DNS, web technologies and information gathering as important components of ethical hacking.

### 8. References

- Networkwalks – Week 2, Project Module 1: Footprinting and Reconnaissance Attacks with Multiple Kali Tools.
- [Kali Linux Official Documentation](https://www.kali.org/docs/)
- [WHOIS](https://www.kali.org/tools/whois/)
- [WhatWeb](https://www.kali.org/tools/whatweb/)
- [DNSRecon](https://www.kali.org/tools/dnsrecon/)

---

**Internship:** Networkwalks Cybersecurity Internship  
**Module:** Week 2 – Project Module 1  
**Focus:** Footprinting and Reconnaissance  
**Environment:** Kali Linux

*All practical activities were conducted within the scope of the provided authorization.*
