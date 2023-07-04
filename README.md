# YARA Rule Generator
Helpful python scripts for yara rule generation. Created by Chat GPT and fine tuned by yours truely.

## malware_ip_rules.py
this will generate a file in the current directory called "malware_ip_addrs.yara" which will contain a set of rules generated from the ip addresses listed collected by the lovely people and processes at the blocklist project. This script will not exceed the 10000 string limit per rule and each rule will be generated with its index number appended to the end of it.
