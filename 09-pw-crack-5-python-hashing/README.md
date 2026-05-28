# PW Crack 5 - Python Hashing Challenge

## Objective

Complete a CyLab Security Academy password cracking challenge by using Python to identify the correct password from a provided dictionary file.

## Tools Used

- Python
- Kali Linux
- Linux command line
- Hashlib
- Dictionary-based password testing

## Summary

In this challenge, I used Python to read a provided dictionary file, remove whitespace from each password candidate, hash each candidate, and compare it against the provided password hash. After identifying the correct password, I used it to recover and submit the challenge flag.

## Key Steps

- Reviewed the provided Python password checker
- Opened and read the provided hash file
- Used Python file handling to read the dictionary file
- Used `.strip()` to clean whitespace from each password candidate
- Hashed each candidate password using MD5 logic
- Compared each generated hash against the provided hash
- Recovered the correct password and solved the challenge

## Skills Practiced

- Python scripting
- File handling
- Hashing
- Password security
- Dictionary-based password attacks
- CTF problem solving
- Linux command line

## Disclaimer

This project was completed in a controlled CTF training environment through CyLab Security Academy.
