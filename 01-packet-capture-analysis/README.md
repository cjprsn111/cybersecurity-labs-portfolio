# Packet Capture Analysis: FTP Data Exfiltration Investigation

## Objective

Analyze a packet capture file using Wireshark to identify suspicious FTP activity and determine whether data exfiltration occurred.

## Tools Used

- Wireshark
- TCP Follow Stream
- Protocol Hierarchy Statistics
- Packet Bytes View

## Summary

In this lab, I analyzed a suspicious packet capture to identify FTP communication, client and server hosts, credentials used, transfer ports, and the file involved in the event. The investigation showed that an employee database CSV file was transferred through FTP.

## Key Findings

- Identified FTP traffic in the packet capture
- Reviewed TCP streams to follow the communication
- Located FTP command activity
- Identified file transfer evidence
- Confirmed the transferred file name: employee_database.csv

## Skills Practiced

- Packet analysis
- Network traffic investigation
- FTP analysis
- TCP stream review
- Data exfiltration analysis
- Security documentation

## Notes

Sensitive-looking data was redacted from screenshots before public posting.
