# CyberGate-RAT-Password-Decryptor
Basic password decryptor for CyberGate Trojan RAT as it uses a insecure proprietary encryption method.

Advisory:
https://www.malvuln.com/advisory/618f28253d1268132a9f10819a6947f2.txt

This well known RAT malware stores credentials using a proprietary insecure encryption routine in its "Settings.ini" file. The recovery procedure is trivial to decrypt stored credentials. theres no key, xor or combined encrypt mechanism and relies on basic SUB, ADD and bitwise operations SHR and SHL.

By malvuln - copyright (c) 2022

MIT License
