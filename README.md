# N47|0N4L [Y83R L34GU3 H4[K$

## Resources

List of resources for finding tools, looking up information about topic
specific things that are generally common during CTF challenges. There is
a lot more on the internet. Being honest, first link that should be here
is your preferred search engine. If you know how to search, find writeups,
find information and learn about new things fast you are good to go. To
the moon obviously!

* https://fareedfauzi.gitbook.io/ctf-checklist-for-beginner/    - Overall
* https://github.com/apsdehal/awesome-ctf                       - Overall
* Linux man pages for cut, uniq, sed, awk

## CRYPTO

Crack crypto
* [CYBER CHEF](https://gchq.github.io/CyberChef/)
* BINARY CONVERTER
* HEX CONVERTER
* BASE64 CONVERTER
* [CEASER CIPHER (ROT)](https://www.dcode.fr/caesar-cipher)
* RAIL FENCE: Change key
* Vigenere: Need key
* [Rumkin](http://rumkin.com/tools/cipher/)

Stego
* EXIFTOOl: Insane for all exif data
* Google
* Linux: File, strings, vim
* Stegsolve
* Steghide
* Binwalk: multiple files; binwalk --dd="." "file"
* DIIT
* 29a.ch photo-forensics

## Enumeration and Exploitation

* Scripting on the fly: Python, or others
* Google
* Pycdc
* GDB
* Ghidra

## Password Cracking

* Hashcat: hashcat file -m # -a # /opt/rockyou.txt; Masking
* [CYBER CHEF](https://gchq.github.io/CyberChef/)
* [Crackstation](https://crackstation.net/)
* [LM HASH / RAINBOW](http://rainbowtables.it64.com/)
* Ophrack: LM/NTLM; NEED WORDLIST

## Web exploitation && Scanning

* Source code
* Devtools
* /opt/directory-list-medium
* Gobuster
* NMAP
* Burpsuite
* Payload all the things
* SQLi: Fareed

## Network Traffic Analysis

* Wireshark:+filtering+export objects+follow packets
* Found decryption key? CTRL+SHIFT+P -> protocol -> add key
* Filter techniques; tcp && !(tcp.port == 80)
* Aircrack-ng
* packetor.com

## Forensics

* Terminal
* Research
* Binwalk
* Hexdump
* Unzip, gzip, tar
