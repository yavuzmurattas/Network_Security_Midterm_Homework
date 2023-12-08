# 4.0 What is Cryptography?

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Cryptography</strong> is the art of secret writing that has been used since Roman times to conceal information or keep messages confidential. Encryption/decryption is a widely used method for keeping information private. Encryption and decryption are the fundamental functions of cryptography. A simple message (plain text) gets turned into an unreadable form called cypher text during encryption. A cypher text is turned into the original text (plaintext) during decryption. Both of these functions are used to secure message against who is not authorized to view the message contents.</p>

## &nbsp;&nbsp;&nbsp;&nbsp;4.1 What is Encryption?

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Through the use of a special key known as an encryption key, data can be mathematically or cryptographically converted into a cypher text using the <strong>encryption</strong> technique. Depending on whether symmetric or asymmetric encryption is being used, either the same key or a separate key can be used to decrypt the data.</p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This section provides a detailed description of open-source tools that can be used to encrypt sensitive data, protecting it from being compromised by simply exposure to attackers. We have divided encryption-based tools into the following four groups in this work:</p>

- Full Disk Encryption
- Encrypted Internet Traffic
- File Encryption Software
- Email encryption

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.1 Full Disk Encryption

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A type of cryptographic encryption called full disc encryption (FDE) is used at the hardware level to encrypt data, files, operating systems, and other programs. The drawback of this is that it can cause delays when memory is severely depleted, particularly with virtual machines where access time may get delayed.  The following is a description of the tools included in this category:</p>

- <p style="text-align: justify;"><strong>LUKS</strong>: FDE tool, called Linux Unified Key Setup (LUKS), is mainly utilized in environments based on Linux. It uses the <strong>dm-crypt</strong> as a backend encryption disc because it is based on the <strong>cryptsetup</strong> program. Greater flexibility in the use of different encryption methods is made possible by LUKS. It also guarantees that password management is used by all parties in a documented, safe manner and facilitates interoperability across different systems.</p>
- <p style="text-align: justify;"><strong>BitLocker</strong>: BitLocker is a full-featured Windows-based Microsoft encryption tool. By default, it employs the AES encryption algorithm in Cypher Block Chaining or the XTS mode with a 128-bit or 256-bit key.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.2 Encrypted Internet Traffic

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It is easy for a user to encrypt their internet traffic. End users can prevent pointless information gathering by using internet encryption solutions. They offer a relatively secure environment for using the internet.</p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>VPN</strong> services such as NordVPN might serve as example for this type of encryption.</p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Secure Shell (SSH)</strong> can also be given as an example to this category.  A cryptographic network protocol called Secure Shell Protocol (SSH) is used to operate network services safely over insecure networks. Command-line execution and remote login are two of its most prominent uses.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.3 File Encryption Software

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;By encrypting the contents of files created and exchanged between users, file encryption tool adds an extra degree of security The following is a description of the tools this category:</p>

- <p style="text-align: justify;"><strong>Encrypto</strong>: Encrypto is a simple-to-use program that shares files using the closest available sharing methods after encrypting them using </strong>AES-256</strong> encryption. Although it is primarily made for Apple products, the software is compatible with Windows and Mac OS.</p>
- <p style="text-align: justify;"><strong>Cryptmount</strong>: This open-source file encryption program may encrypt a specific filing system and is compatible with Linux.</p>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.4 Email Encryption

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Emails are encrypted while being transmitted over the internet, but the main content is still in plain text, leaving it vulnerable to theft by outsiders. Both end-to-end and transport level encryption are necessary to foil attempts to access information by outside agents. Because popular email services like Outlook and Gmail do not by default offer end-to-end encryption, encrypting emails requires the use of specialized software. Here is a discussion of a few email encryption tools.</p>

- <p style="text-align: justify;"><strong>Mailvelope</strong>: End-to-end encryption of email traffic is achieved through the use of this open-source software. Mailvelope is compatible with popular web email applications including Chromium, Mozilla Firefox, and others. Web email applications with OpenPGP capability are implemented by Mailvelope.</p>
- <p style="text-align: justify;"><strong>ProtonMail</strong>: An encrypted email service that is accessible since 2013. Before moving to the ProtonMail servers, it employs end-user side encryption to regulate user data and email content. </p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Pretty Good Privacy (PGP)</strong> is an encryption program that offers cryptographic privacy and authentication for data communication, in addition to the categories mentioned above. PGP is used to improve the security of e-mail communications as well as to sign, encrypt, and decrypt files, directories, texts, e-mails, even entire disc partitions. PGP and related programs encrypt and decrypt data in accordance with the <strong>OpenPGP standard (RFC 4880)</strong>, which is an open standard of PGP encryption software.</p>

<p style="text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Crypto API</strong> in Kernel can also be used. A wide range of cryptographic cyphers, additional data transformation techniques, and methods to invoke these are all provided via Crypto API in Kernel.</p>
