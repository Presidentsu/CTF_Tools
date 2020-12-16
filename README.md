# CTF Tools

This has all the tools I use when I participate in CTF's.
These tools can be used for general purposes (I mean related to general tasks related to computer and system security)

## Cryptography

1. Lets start with challenges related to encoding or known cipher we can use [Cryptii](https://cryptii.com/) or [CyberChef](https://gchq.github.io/CyberChef/).
2. You can use the SimpleRSA script for RSA encryption (Creds: John H).
3. LC4 encryption and Decryption [link](https://github.com/dstein64/LC4/blob/master/documentation.md).
4. Esoteric languages I use [tio online tool](https://tio.run) it has languages such as brainfuck, JSfuck (Yeah I know offensive I you have a look at those I am sure you would cuss xD).
5. Hashes:
	- If the hash is known I meam of most used word for password I use [Crackstation](www.crackstation.net) online tools has DB of all commonly used passowrds and its hashes.
	-	If the hash is unknown and if we were left with no other choice than using bruteforce I use [hashcat](https://hashcat.net/hashcat/)
6. Cryptography attacks I refer to [mithi's simple cryptography](https://github.com/mithi/simple-cryptography).

## Networking

1. Wireshark works for both linux and windows - [link](https://www.wireshark.org/download.html).
2. Network Mined works for windows - [link](https://www.netresec.com/)
3. tcpdump Command Line Utility Tool - [link](https://www.tcpdump.org/)
4. OpenSSL - [link](https://github.com/openssl/openssl)
5. zip2john extracts hash of a password protected zip file- [link](https://github.com/openwall/john/blob/bleeding-jumbo/src/zip2john.c)

## Steganography

1. Steghide - linux package use (apt install steghide).
2. zsteg - Linux package use (apt install zsteg).
3. pngcheck - [link](http://www.libpng.org/pub/png/apps/pngcheck.html)
4. Audacity - [link](https://sourceforge.net/projects/audacity/)
5. Opensteg - [link](https://www.openstego.com/)
6. Mp3stego - [link](https://www.petitcolas.net/steganography/mp3stego/)
7. Snow steg - [link](http://www.darkside.com.au/snow/)

## Forensics

### Image forensics
1. fotoforensics - [link](http://fotoforensics.com/)
2. exfitools - [link](https://exiftool.org/)
3. stegsolve jar - [link](http://www.caesum.com/handbook/Stegsolve.jar)

### Memory forensics.
1. Voltality - [link](https://github.com/volatilityfoundation/volatility)
2. The Sleuth Kit - [link](http://www.sleuthkit.org)

### Misc Forensics tools
1. dd - linux utility tool
2. binwalk - can be used to find if any hidden files.
3. Foremost - [link](http://foremost.sourceforge.net/)
4. Hex edit (both online and offline) - [link](https://hexed.it/)

## Reversing

1. IDA Free(cuz I am broke :-( ) - [link](https://www.hex-rays.com/products/ida/support/download_freeware/)
2. Ghidra (Free tool by NSA. Thank you NSA <3 for the tools for broke peeps like me xD :-{ )- [link](https://ghidra-sre.org/)
3. gdb - [link](https://www.gnu.org/software/gdb/download/)
4. OllyDbg - [link](http://www.ollydbg.de/)
5. Objdump - linux tool use `apt install objdump`
6. Hooper similar to IDA - [link](https://www.hopperapp.com/download.html)
7. rdare2 - linix tool [link](https://www.radare.org/r/)
8. ILSpy for .NET - [git clone link](https://github.com/icsharpcode/ILSpy.git)
9. strace and ltrace tools - linux utility tool `apt install strace && apt install ltrace`
10. strings - linux utility tool
11. PE explorer - Windows tool  [link](http://www.heaventools.com/)
12. PE Id - [link](https://www.aldeid.com/wiki/PEiD)
13. pwntools - python library [link](https://github.com/Gallopsled/pwntools)
