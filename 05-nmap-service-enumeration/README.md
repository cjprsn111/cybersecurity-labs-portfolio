# Nmap Port Scan and Service Enumeration

## Objective

Use Nmap to scan a Metasploitable virtual machine and document open ports, services, and versions.

## Tools Used

- Nmap
- Kali Linux
- Metasploitable

## Command Used

```bash
nmap -sV -sC -oA metasploitable_scan <target-ip>
```

## Summary

In this lab, I performed service enumeration against a Metasploitable VM. I used Nmap service detection, default scripts, and output logging to identify exposed services and save the results in multiple formats.

## Key Findings

- Identified open TCP ports
- Detected service versions
- Generated Nmap scan logs
- Reviewed exposed services for vulnerability assessment

## Skills Practiced

- Port scanning
- Service enumeration
- Nmap output logging
- Network reconnaissance
- Vulnerability assessment preparation
