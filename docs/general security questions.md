What is Cryptography?
<details>
  <summary>Answer</summary>
  Cryptography is the practice and study of techniques for securing information and communication mainly to protect the data from third parties that the data is not intended for.
</details>

What is the difference between Symmetric and Asymmetric encryption?
<details>
  <summary>Answer</summary>
  
| Basis of Comparison        | Symmetric Encryption           | Asymmetric Encryption  |
| ------------- |:-------------:| -----:|
| Encryption key     | Same key for encryption & decryption | Different keys for encryption & decryption |
| Performance | Encryption is fast but more vulnerable | Encryption is slow due to high computation |
| Algorithms | DES, 3DES, AES and RC4 | Diffie-Hellman, RSA |
| Purpose | Used for bulk data transmission | Often used for securely exchanging secret keys |
</details>

What is the difference between IDS and IPS?
<details>
  <summary>Answer</summary>
  IDS is Intrusion Detection System and it only detects intrusions and the administrator has to take care of preventing the intrusion. Whereas, in IPS i.e., Intrusion Prevention System, the system detects the intrusion and also takes actions to prevent the intrusion.
</details>

Explain the CIA triad.
<details>
  <summary>Answer</summary>
  CIA stands for Confidentiality, Integrity, and Availability. CIA is a model that is designed to guide policies for Information Security. It is one of the most popular models used by organizations.

### Confidentiality

The information should be accessible and readable only to authorized personnel. It should not be accessible by unauthorized personnel. The information should be strongly encrypted just in case someone uses hacking to access the data so that even if the data is accessed, it is not readable or understandable.

### Integrity

Making sure the data has not been modified by an unauthorized entity. Integrity ensures that data is not corrupted or modified by unauthorized personnel. If an authorized individual/system is trying to modify the data and the modification wasn’t successful, then the data should be reversed back and should not be corrupted.

### Availability

The data should be available to the user whenever the user requires it. Maintaining of Hardware, upgrading regularly, Data Backups and Recovery, Network Bottlenecks should be taken care of.
</details>

What is the difference between encoding, encrypting, and hashing?
<details>
  <summary>Answer</summary>

### Encoding 
In the Encoding method, data is transformed from one form to another. The main aim of encoding is to transform data into a form that is readable by most of the systems or that can be used by any external process.
It can’t be used for securing data, various publicly available algorithms are used for encoding.

Encoding can be used for reducing the size of audio and video files. Each audio and video file format has a corresponding coder-decoder (codec) program that is used to code it into the appropriate format and then decodes for playback.

Example: ASCII, BASE64, UNICODE

### Encryption 
Encryption in encoding technique in which message is encoded by using encryption algorithm in such a way that only authorized personnel can access the message or information.


It is a special type of encoding that is used for transferring private data, for example sending a combination of username and password over the internet for email login.

In encryption, data to be encrypted(called plain-text) is transformed using an encryption algorithm like AES encryption or RSA encryption using a secret key called cipher. The encrypted data is called cipher-text, and finally, the secret key can be used by the intended recipient to convert it back to plain-text.

There are two types of encryption algorithms – symmetric and asymmetric encryption.
In case of symmetric encryption data is encoded and decoded with the help of same key, for example AES encryption algorithm but in case of asymmetric encryption algorithm, data is encrypted with help of two keys, namely public and private key, for example. RSA algorithm

### Hashing
In hashing, data is converted to the hash using some hashing function, which can be any number generated from string or text. Various hashing algorithms are MD5, SHA256. Data once hashed is non-reversible.

Hash function can be any function that is used to map data of arbitrary size to data of fixed size. The data structure hash table is used for storing of data.

For example: When you send pictures and text messages over WhatsApp over StackOverflow(posting in questions), images are sent to different server and text is sent to a different server for efficiency purposes. So for verifying images that the images are not tampered in between data transfer over the internet, hashing algorithm like MD5 can be used. 
</details>

What is a Firewall and why is it used?
<details>
  <summary>Answer</summary>
  A Firewall is a network security system set on the boundaries of the system/network that monitors and controls network traffic. Firewalls are mainly used to protect the system/network from viruses, worms, malware, etc. Firewalls can also be to prevent remote access and content filtering.
</details>

What is the difference between VA(Vulnerability Assessment) and PT(Penetration Testing)?
<details>
  <summary>Answer</summary>
  
  ### Vulnerability Assessment
  The process of finding flaws on the target. Here, the organization knows that their system/network has flaws or weaknesses and want to find these flaws and prioritize the flaws for fixing.

### Penetration Testing
The process of finding vulnerabilities on the target. In this case, the organization would have set up all the security measures they could think of and would want to test if there is any other way that their system/network can be hacked.
</details>

What is a three-way handshake?
<details>
  <summary>Answer</summary>
  A three-way handshake is a method used in a TCP/IP network to create a connection between a host and a client. It’s called a three-way handshake because it is a three-step method in which the client and server exchanges packets. The three steps are as follows:

  1. The client sends a SYN(Synchronize) packet to the server check if the server is up or has open ports
  2. The server sends SYN-ACK packet to the client if it has open ports
  3. The client acknowledges this and sends an ACK(Acknowledgment) packet back to the server
</details>

What is traceroute? Why is it used?
<details>
  <summary>Answer</summary>
  Traceroute is a tool that shows the path of a packet. It lists all the points (mainly routers) that the packet passes through. This is used mostly when the packet is not reaching its destination. Traceroute is used to check where the connection stops or breaks to identify the point of failure.
</details>

What is the difference between HIDS and NIDS?
<details>
  <summary>Answer</summary>
  HIDS(Host IDS) and NIDS(Network IDS) are both Intrusion Detection System and work for the same purpose i.e., to detect the intrusions. The only difference is that the HIDS is set up on a particular host/device. It monitors the traffic of a particular device and suspicious system activities. On the other hand, NIDS is set up on a network. It monitors traffic of all device of the network.
</details>

Explain Data Leakage
<details>
  <summary>Answer</summary>
  Data Leakage is an intentional or unintentional transmission of data from within the organization to an external unauthorized destination. It is the disclosure of confidential information to an unauthorized entity. Data Leakage can be divided into 3 categories based on how it happens:

  1. Accidental Breach: An entity unintentionally send data to an unauthorized person due to a fault or a blunder
  2. Intentional Breach: The authorized entity sends data to an unauthorized entity on purpose
  3. System Hack: Hacking techniques are used to cause data leakage
  
  Data Leakage can be prevented by using tools, software, and strategies known as DLP(Data Leakage Prevention) Tools.
</details>

What is a Brute Force Attack? How can you prevent it?
<details>
  <summary>Answer</summary>
  Brute Force is a way of finding out the right credentials by repetitively trying all the permutations and combinations of possible credentials. In most cases, brute force attacks are automated where the tool/software automatically tries to login with a list of credentials. There are various ways to prevent Brute Force attacks. Some of them are:

  - Password Length: You can set a minimum length for password. The lengthier the password, the harder it is to find.
  - Password Complexity: Including different formats of characters in the password makes brute force attacks harder. Using alpha-numeric passwords along with special characters, and upper and lower case characters increase the password complexity making it difficult to be cracked.
   - Limiting Login Attempts: Set a limit on login failures. For example, you can set the limit on login failures as 3. So, when there are 3 consecutive login failures, restrict the user from logging in for some time, or send an Email or OTP to use to log in the next time. Because brute force is an automated process, limiting login attempts will break the brute force process.
</details>

What is Port Scanning?
<details>
  <summary>Answer</summary>
  Port Scanning is the technique used to identify open ports and service available on a host. Hackers use port scanning to find information that can be helpful to exploit vulnerabilities. Administrators use Port Scanning to verify the security policies of the network.
</details>

What are the different layers of the OSI model?
<details>
  <summary>Answer</summary>
  An OSI model is a reference model for how applications communicate over a network. The purpose of an OSI reference is to guide vendors and developers so the digital communication products and software programs can interoperate.

Following are the OSI layers:different OSI layers-cybersecurity interview questions-edureka

### Physical Layer
Responsible for transmission of digital data from sender to receiver through the communication media,

### Data Link Layer
Handles the movement of data to and from the physical link. It is also responsible for encoding and decoding of data bits.

### Network Layer
Responsible for packet forwarding and providing routing paths for network communication.

### Transport Layer
Responsible for end-to-end communication over the network. It splits the data from the above layer and passes it to the Network Layer and then ensures that all the data has successfully reached at the receiver’s end.

### Session Layer
Controls connection between the sender and the receiver. It is responsible for starting, ending, and managing the session and establishing, maintaining and synchronizing interaction between the sender and the receiver.

### Presentation Layer
It deals with presenting the data in a proper format and data structure instead of sending raw datagrams or packets.

### Application Layer
It provides an interface between the application and the network. It focuses on process-to-process communication and provides a communication interface.
</details>

What is a VPN?
<details>
  <summary>Answer</summary>
  VPN stands for Virtual Private Network. It is used to create a safe and encrypted connection. When you use a VPN, the data from the client is sent to a point in the VPN where it is encrypted and then sent through the internet to another point. At this point, the data is decrypted and sent to the server. When the server sends a response, the response is sent to a point in the VPN where it is encrypted and this encrypted data is sent to another point in the VPN where it is decrypted. And finally, the decrypted data is sent to the client. The whole point of using a VPN is to ensure encrypted data transfer.
</details>

What is the difference between a threat, a vulnerability, and a risk?
<details>
  <summary>Answer</summary>

### Threat
Someone with the potential to harm a system or an organization
### Vulnerability
Weakness in a system that can be exploited by a potential hacker
### Risk
Potential for loss or damage when threat exploits a vulnerability
</details>

What are black hat, white hat and grey hat hackers?
<details>
  <summary>Answer</summary>

### Black hat hackers
Known for having vast knowledge about breaking into computer networks. They can write malware which can be used to gain access to these systems. This type of hackers misuse their skills to steal information or use the hacked system for malicious purpose. 

### White hat hackers
Use their powers for good deeds and so they are also called Ethical Hackers. These are mostly hired by companies as a security specialist that attempts to find and fix vulnerabilities and security holes in the systems. They use their skills to help make the security better. 

### Grey hat hackers
Are an amalgamation of a white hat and black hat hacker. They look for system vulnerabilities without the owner’s permission. If they find any vulnerabilities, they report it to the owner. Unlike Black hat hackers, they do not exploit the vulnerabilities found. 
</details>

Explain MITM attack and how to prevent it?
<details>
  <summary>Answer</summary>
A MITM(Man-in-the-Middle) attack is a type of attack where the hacker places himself in between the communication of two parties and steal the information. Suppose there are two parties A and B having a communication. Then the hacker joins this communication. He impersonates as party B to A and impersonates as party A in front of B. The data from both the parties are sent to the hacker and the hacker redirects the data to the destination party after stealing the data required. While the two parties think that they are communicating with each other, in reality, they are communicating with the hacker.

You can prevent MITM attack by using the following practices:

- Use VPN
- Use strong WEP/WPA encryption
- Use Intrusion Detection Systems
- Force HTTPS
- Public Key Pair Based Authentication
</details>

Explain DDOS attack and how to prevent it?
<details>
  <summary>Answer</summary>
A DDOS(Distributed Denial of Service) attack is a cyberattack that causes the servers to refuse to provide services to genuine clients. DDOS attack can be classified into two types:

1. Flooding attacks: In this type, the hacker sends a huge amount of traffic to the server which the server can not handle. And hence, the server stops functioning. This type of attack is usually executed by using automated programs that continuously send packets to the server.
2. Crash attacks: In this type, the hackers exploit a bug on the server resulting in the system to crash and hence the server is not able to provide service to the clients.

You can prevent DDOS attacks by using the following practices:

- Use Anti-DDOS services
- Configure Firewalls and Routers
- Use Front-End Hardware
- Use Load Balancing
- Handle Spikes in Traffic
</details>

What is an ARP and how does it work?
<details>
  <summary>Answer</summary>
Address Resolution Protocol (ARP)is a protocol for mapping an Internet Protocol address (IP address) to a physical machine address that is recognized in the local network.

When an incoming packet destined for a host machine on a particular local area network arrives at a gateway, the gateway asks the ARP program to find a physical host or MAC address that matches the IP address.

The ARP program looks in the ARP cache and, if it finds the address, provides it so that the packet can be converted to the right packet length and format and sent to the machine.

If no entry is found for the IP address, ARP broadcasts a request packet in a special format to all the machines on the LAN to see if one machine knows that it has that IP address associated with it.
</details>

What is port blocking within LAN?
<details>
  <summary>Answer</summary>
Restricting the users from accessing a set of services within the local area network is called port blocking.

Stopping the source to not to access the destination node via ports. As the application works on the ports, so ports are blocked to restricts the access filling up the security holes in the network infrastructure.
</details>

What is a Botnet?
<details>
  <summary>Answer</summary>
A Botnet is a number of devices connected to the internet where each device has one or more bots running on it. The bots on the devices and malicious scripts used to hack a victim. Botnets can be used to steal data, send spams and execute a DDOS attack.
</details>

What are salted hashes?
<details>
  <summary>Answer</summary>
Salt is a random data. When a properly protected password system receives a new password, it creates a hash value of that password, a random salt value, and then the combined value is stored in its database. This helps to defend against dictionary attacks and known hash attacks.

Example: If someone uses the same password on two different systems and they are being used using the same hashing algorithm, the hash value would be same, however, if even one of the system uses salt with the hashes, the value will be different.
</details>

What is data protection in transit vs data protection at rest?
<details>
  <summary>Answer</summary>

| Data Protection in transit  | Data protection at rest |
| ------------- | ------------- |
| When data is going from server to client  | When data just exists in its database or on its hard drive  |
| Effective Data protection measures for in-transit data are critical as data is less secure when in motion  | Data at rest is sometimes considered to be less vulnerable than data in transit  |
</details>

What is 2FA and how can it be implemented for public websites?
<details>
  <summary>Answer</summary>
An extra layer of security that is known as “multi-factor authentication“.

Requires not only a password and username but also something that only, and only, that user has on them, i.e. a piece of information only they should know or have immediately to hand – such as a physical token.

Authenticator apps replace the need to obtain a verification code via text, voice call or email.
</details>

What is the difference between VPN and VLAN?
<details>
  <summary>Answer</summary>

| VPN | VLAN |
| ------------- | ------------- |
| Helps to group workstations that are not within the same locations into the same broadcast domain  | Related to remote access to the network of a company  |
| Means to logically segregate networks without physically segregating them with various switches  | Used to connect two points in a secured and encrypted tunnel  |
| Saves the data from prying eyes while in transit and no one on the net can capture the packets and read the data | Does not involve any encryption technique but it is only used to slice up your logical network into different sections for the purpose of management and security |
</details>

Explain Phishing and how to prevent it?
<details>
  <summary>Answer</summary>
Phishing is a Cyberattack in which a hacker disguises as a trustworthy person or business and attempt to steal sensitive financial or personal information through fraudulent email or instant message.

You can prevent Phishing attacks by using the following practices:
- need to put stuff here
</details>

Explain SQL Injection and how to prevent it?
<details>
  <summary>Answer</summary>
SQL Injection (SQLi) is a code injection attack where an attacker manipulates the data being sent to the server to execute malicious SQL statements to control a web application’s database server, thereby accessing, modifying and deleting unauthorized data. This attack is mainly used to take over database servers.

You can prevent SQL Injection attacks by using the following practices:

- Use prepared statements
- Use Stored Procedures
- Validate user input
</details>

How do you go about securing a server?
<details>
  <summary>Answer</summary>
You might want to break this answer down into steps, especially if it refers to a specific type of server. Your answer will give a glimpse into your decision-making abilities and thought process. There are multiple ways to answer this question, just as there are multiple ways to secure a server. You might reference the concept of trust no one or the principle of least privilege. Let your expertise guide your response to this question and the others following it.
</details>

Why is DNS monitoring important?
<details>
  <summary>Answer</summary>
DNS monitoring is prudent because DNS queries are a data-exfiltration vector from networks that allow any host to communicate to the Internet on Port 53. As well as it can be used to detect infected machine communicating with command and controol servers.
</details>

How would you strengthen user authentication?
<details>
  <summary>Answer</summary>
  need to write an Answer
</details>

What tech blogs do you folow / where do you get your news?
<details>
  <summary>Answer</summary>
  need to write an Answer
</details>

What does Zero Trust mean?
<details>
  <summary>Answer</summary>
  need to write an Answer
</details>
