#3.0 Anti-Virus Software

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Malware</strong> is any software that is intentionally designed to disrupt a computer, server, client, or computer network, leak private information, gain unauthorized access to information or systems, deprive access to information, or interfere with the user's computer security and privacy. Malware refers to computer viruses as well as many other types of harmful software, such as computer worms, trojan horses, keyloggers, and so on. Malwares can infiltrate the system via e-mails by using phishing methods, and also via files which are downloaded, usb flash memories, etc.</p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You can be protected from malware thanks to antivirus software. <strong>Anti-virus software</strong> detects, finds, and removes malware from your computer while also ensuring that it functions properly. Anti-virus software typically employs a variety of strategies in virus removal solutions, such as scanning files and matching files to existing virus dictionaries/databases to find matches and determine anomalous computer activity, such as slow computer performance.</p>

## &nbsp;&nbsp;&nbsp;&nbsp;3.1 Anti-Virus Methods

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antivirus programs identify viruses using a variety of detection methods. Some of the methods are described in the following sub-sections.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1.1 Signature Detection Programs

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These programs search RAM and files for signatures specific to a particular virus and, if found, publish a corresponding message. The problem of such anti-virus programs is that they only detect viruses which the developers of such programs know.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1.2 Data Analyzing

<p style="text-align:justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data analyzing includes auditors. The consequences are manifested in data changes that should not be changed. For the auditor, the fact that data has changed indicates the presence of malware. Auditors check the integrity of the data and assess whether malware is present in the computer environment in the event of a breach of integrity.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1.3 Cyclic Redundancy Check

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Cyclic Redundancy Check (CRC) process is based on calculating the checksums of the files on the disc. These Cyclic Redundancy Check values are then kept in the antivirus database, along with some other information, such as the file's length and the date it was last changed. These scanners compare the data in the database to the calculated values. Assume the information in the database file discards the actual values. CRC scanners indicate that the file has been modified or is infected with a virus in this situation. Because their database does not contain information about viruses in new files, CRC scanners cannot detect them immediately. Furthermore, regular viruses exploit the vulnerability in CRC scanners, infecting only recently created files and so remaining invisible to them.</p>
 
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1.4 Analytical Scrutinize

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These programs are among the most reliable tools for virus protection since they remember the initial state of programs, directories, and disc system areas when the computer was not affected with a virus. Then, occasionally or at the user's request, they compare the current condition to the original. These programs have advanced algorithms, detect stealth viruses, and even clean up changes to the program’s scanned version from the changes introduced by the virus.</p>

## &nbsp;&nbsp;&nbsp;&nbsp;3.2 Anti-Virus Evasion Techniques

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cybercriminals have developed various strategies to evade anti-virus systems in order to achieve their goals. These include:</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.2.1 Code Packing and Encryption

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hackers design special utilities for packaging and encrypting data, such as CryptExe, Exeref, and PolyCrypt. Since the vast majority of worms and trojans are encrypted and packaged, to detect packed and encrypted worms and trojans, the antivirus program must either add new unpacking and decoding methods or add new signatures for each malicious program sample.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.2.2 Code Mutation

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cybercriminals try to camouflage their dangerous software by mixing a trojan virus's code and spam instructions, so that the code takes on a different appearance while preserving the trojan's original functionality. Code mutation can occur in real time at times. This approach was exploited by the Warezov mail worm, which created major problems for users.</p>

