# Task 2 – Network Security & Scanning

## Objective

The objective of this task was to understand the fundamentals of network reconnaissance and scanning using commonly used cybersecurity tools. The task also involved exploring the Greenbone Vulnerability Management (GVM/OpenVAS) interface for vulnerability assessment.

---

## Tools Used

* Kali Linux
* Google Search (Google Dorking)
* WHOIS
* NSLOOKUP
* Nmap
* Greenbone Vulnerability Manager (GVM/OpenVAS)

---

## Activities Performed

### 1. Google Dorking

Performed basic Google Dorking using search operators such as:

* `site:`
* `inurl:`

This demonstrated how search operators can be used to locate publicly indexed information more effectively.

### 2. WHOIS Lookup

Used the `whois` command to retrieve publicly available domain registration information.

Example:

```bash
whois example.com
```

### 3. DNS Lookup

Used `nslookup` to obtain DNS-related information for a domain.

Example:

```bash
nslookup example.com
```

### 4. Network Scanning using Nmap

Performed different types of scans on the local system.

Basic Scan:

```bash
nmap localhost
```

Service Version Detection:

```bash
sudo nmap -sV localhost
```

Operating System Detection:

```bash
sudo nmap -O localhost
```

Generated a scan report using:

```bash
sudo nmap -sV localhost -oN nmap_report.txt
```

### 5. Greenbone Vulnerability Manager (GVM)

Successfully started the GVM services and accessed the Greenbone Security Assistant web interface through the browser.

The dashboard was accessed successfully, confirming that the vulnerability assessment environment was operational. (A vulnerability scan was not performed because the default scan configuration was still synchronizing.)

---

## Files Included

* README.md
* nmap_report.txt
* Screenshots of:

  * Google Dorking
  * WHOIS
  * NSLOOKUP
  * Nmap Basic Scan
  * Nmap Service Version Detection
  * Nmap OS Detection


---

## Learning Outcomes

* Learned basic reconnaissance techniques.
* Understood how WHOIS and DNS lookups provide information about domains.
* Performed network scanning using Nmap.
* Identified open ports, running services, and operating system information.
* Explored the Greenbone Vulnerability Management interface for vulnerability assessment.

---

## Conclusion

This task provided practical exposure to reconnaissance and network scanning techniques using industry-standard cybersecurity tools. It strengthened my understanding of information gathering, network analysis, and the use of GVM as a vulnerability management platform.
