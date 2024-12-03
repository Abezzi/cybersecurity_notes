# Introduction to cybersecurity

problem: 1 attack every 39s
solution: security analyst to protect the organization

## 1.1

- cybersecurity: is the ongoing effort to protect individuals, organizations and governments from digital attacks by protecting networked systems and data from unauthorized use or harm.

Cybersecurity has three levels of protection: 
 
- Personal (identity, data, computing devices) 
- Organizational (reputation, data and customers)
- Government (national security, economic stability, safety and well being of citizens)

Offline identity: real-life persona (real name, age, address)
Online identity: you online (username and how you present yourself online)

## 1.2 Organizational data

- **traditional data**: details relating buying and selling, production activities and basic organizational operations such as any information used to make employment decisions.
- **intellectual property**: such as patents, trademark and new product plans, which allow an organization to gain economic advantage over its competitors. This information is often considered a trade secret and losing it could prove disastrous for the future of a company.
- **Financial data**: such as income statements, balance sheets and cash flow statements, which provide insight into the health of a company.

**internet of things (IoT) and big data**: IoT is a large network of physical objects, such as sensors, software and other equipment. All of these things are connected to the internet, with the ability to collect and share data. And given that storage options are expanding through the cloud and virtualisation, it's no surprise that the emerge of IoT has led to an exponential growth in data, creating a new area of interest in technology and business called 'Big Data'.

## the cube (Jhon McCumber 1991)

Helps organizations establish and evaluate information security initiatives by considering all of the related factors that impact them. This security model has three dimensions:

1. the foundational principles for protecting information systems.
2. the protection of information in each of its possible states.
3. the security measures used to protect data.

## elements of each dimension:

### Foundational principles for protecting information
- **confidentiality** is a set of rules that prevents sensitive information from being disclosed to unauthorized people, resources and process. Methods to ensure Confidentiality include data encryption, indentity proofing. and two factor authentication.
- **integrity**: ensures that system information processes are protected from intentional or accidental modification. One way to ensure integrity is to use a hash function or checksum.
- **availability**: means that authorized users are able to access systems and data when and where needed and those that do not meet established conditions, are not. This can be achieved by maintaining equipment, performing hardware repairs, keeping operating systems and software up to date, and creating backups

### The protection of information in each state
- **Processing** refers to data that is being used to perform an operation such as updating a database record (data in process)
- **Storage** refers to data stored in memory or on a permanent storage device such as a hard drive, solid state drive or USB drive (data at rest)
- **Transmission** refers to data traveling between information systems (data in transit)

### The security measures used to protect data
- **Awareness, training and education** are the measures put in place by an organization to ensure that users are knowledgable about potential security threat and the actions they can take to protect information systems.
- **Technology** refers to the software- and hardware-based solutions designed to protect information systems such as firewalls, which continuously monitor your network in search of possible malicious incidents.
- **Policy and procedure** refers to the administrative controls that provide a foundation for how an organization implements information assurance, such as incident response plans and best practice guidelines.

## Data security breaches

A security breach is an incident that results in unauthorized  access to data, applications, services or devices, exposing private information that attackers can use for financial gain or other advantages
But there are many way to protect yourself and your organization. It's important to be aware of common cyber threats and remain vigilant so that you don't become the next victim

## types of hackers
- **Amateurs**: inexperience hackers or script kiddies, people who use existing tools or instruction found in the internet to launch attacks
- **Hackers**: break into computer systems or networks to gain access. Depending on the intent of their break in, they can be classified as:
  - **White Hat Attackers**: break into networks or computers systems to identify any weaknesses so that the security of a system or network can be improved. These break-ins are done with prior permission and any result are repoerted back to the owner.
  - **Gray Hat Attackers**: may set out to find vulnerabilities in a system but they will only report their findings to the owners of a system if doing so coincides with their agenda. Or they might even publish details about the vulnerability on the internet so that other attackers can exploit it.
  - **Black Hat Attackers**: take advantage of any vulnerability for illegal personal, financial or political gain
- **Organized Hackers**: these attackers include organization of cyber criminals, hacktivist, terrorist and state-sponsored hackers. They are usually highly sophisticated and organized, and may even provide cybercrime as a a service to other criminals.
  - **Hacktivist** make political statements to create awareness about issues that are important to them.
  - **State-sponsored** attackers gather intelligence or commit sabotage on behalf of their government. They are usually highly trained and well-funded and their attacks are focused on specific goals that are beneficial to their government

## Cyberwarfare
is the use of technology to penetrate and attack another nation's computer systems and network in an effort to cause damage or disrupt services such as shutting down a power grid

## Malware

Malicious software or malware is any code that can be used to steal data, bypass access controls, or cause harm to or compromise a system. Knowing what the different types are and how they spread is key to containing and removing them.

- **Spyware**: track and spy you, log your key presses and capture almost any of your data. Often bundles itself with legitimate software or trojan horses
- **Adware**: automatically deliver advertisements to a user. Its common to come with spyware
- **Backdoor**: this type of malware is used to gain unauthorized access by bypassing the normal authentication procedures to access a system, as a result hackers can gain remote access to resources within an application and issue remote system commands. Works in the background and are difficult to detect
- **Ransomware**: designed to hold a computer system or the data it contains captive until a payment is made. Usually by encrypting your data so that you can't access it. Often spread through phishing emails that encourage you to download a malicious attachment or through a software vulnerability
- **Scareware**: uses 'scare' tactics to trick you into taking specific actions to agree to execute the specific program to infect your system with malware
- **Rootkit: this malware is deigned to modify the operating system to create a backdoor, which attackers can then use to access your computer remotely. Most rootkits take advantage of software vulnerabilities to gain access to resources that normally shouldn't be accessible(privilege escalation) and modify system files. Can also modify system forensics and monitoring tools, making them very hard to detect. In most cases, a computer infected by a rootkit has to be wiped and any required software reinstalled.
- **Virus**: is a type of computer program that, when executed, replicates and attaches itself to other executable files, such as a document, by inserting its own code. Most viruses require end-user interaction to initiate activation and can be written to act on a specific date or time. Can be harmless or very destructive. Can also be programmed to mutate in order to avoid detection. Spreads by USB, optical media, network shares, email, etc.
- **Trojan horse**: malware carries out malicious operating by masking its true intent. It might appear legitimate but is, in fact, very dangerous. Trojan exploit your user privileges and are most often found in image files, audio files or games. Unlike viruses, Trojans do not self-replicate but act as a decoy to sneak malicious software past unsuspecting users.
- **Worms**: replicates itself in order to spread from one computer to another. Unlike a virus, which requires a host program to run, worms can run by themselves. Other than the initial infection of the host, they do not require user participation and can spread very quickly over the network. Have a similar patten: exploit system vulnerabilities, they have a way to propagate themselves, and they all contain malicious code (payload) to cause damage to computer systems or networks. Worms are responsible for some of the most devastating attacks on the internet. In 2001, the Code red worm had infected over 300.000 servers in just 19 hours.

## Symptoms of malware

- increase in CPU usage
- freeze or crash often
- decrease of web browsing speed
- unexplainable problems with your network connections
- modified or deleted files
- the presence of unknown files, programs or desktop icons
- unknown processes running
- programs turning off or reconfiguring themselves
- emails being sent without your knowledge or consent

## methods of infiltration

- social engineering is the manipulation of people into performing actions or divulging confidential information. For example, an attacker will call an authorized employee with an urgent problem that requires immediate network access and appeal to the employee;s vanity or greed or invoke authority by using name-dropping techniques in order to gain access
  - pretexting this is when an attacker calls an individual and lies to them in an attempt to gain access to privileges data. For example, pretending to need a person's personal or financial data in order to confirm their identity
  - tailgating: this is when an attacker quickly follows an authorized person into a secure, physical location
  - something for something (quid pro quo): this is when an attacker request personal information from a person in exchange for something, like a free gift
- **denial-of-service (DoS)**: attacks are a type of network attack that is relatively simple to carry out, even by an unskilled attacker. A DoS attack result in some sort of interruption of network service to users, devices or applications.
  - **overwhelming quantity of traffic** this is when a network, host or application is sent an enormous amount of data at a rate which it cannot handle. This causes a slowdown in transmission or response, or the device or service to crash.
  - **Maliciously formatted packets** a packet is a collection of data that flows between a source and a receiver computer or application over a network, such as the internet. When a maliciously formatted packet is sent, the receiver will be unable to handle it. For example, if an attacker forward packets containing errors or improperly formatted packets that cannot be identified by an application, this will cause the receiving device to run very slowly or crash.
- **Distributed DoS**: is similar to DoS attack but originates from multiple, coordinated sources. For example:
  - an attacker builds a network (botnet) of infected hosts called zombies, which are controlled by handler systems.
  - the zombie computer will constantly scan and infect more hosts, creating more and more zombies.
  - when ready, the hacker will instruct the handler systems to make the botnet of zombies carry out DDoS attacks.
- **Botnet**: a group of bots, connected through the internet, that can be controlled by a malicious individual or group. It can have tens of thousands, or even hundreds of thousands, of bots that are typically controlled through a command and control server. These bots can activated to distribute malware, launch DDoS attacks, distribute spam email, or execute brute-force password attacks. Cybercriminals will often rent out botnets to third parties for nefarious purposes. Many organizations. Like Cisco force network activities through botnet traffic filters to identify any botnet locations.
- **On-Path Attacks** intercept or modify communications between two devices, such as a web browser and a web server, either to collect information from or to impersonate one of the devices. this type of attack is also referred to as a man-in-the-middle (MitM) or man-in-the-mobile (MitMo) attack.
- **SEO Poisoning** uses SEO to push malicious sites to higher up the ranks of search results. The most common goal of SEO poisoning is to increase traffic to malicious sites that may host malware or attempt social engineering.
- **Wi-Fi password cracking** 
- **Password attacks** entering a username and password is one of the most popular forms of authenticating to a web site. Therefore, uncovering your password is an easy way for cybercriminals to gain access to your most valuable information.
  - **Password spraying** this technique attempts to gain access to a system by 'spraying' a few commonly used passwords across a large number of accounts. For example, a cybercriminal uses 'Password123' with many usernames before trying again with a second commonly-used password, such as 'qwerty' this technique allows the perpetrator to remain undetected as they avoid frequent account lockouts
  - **Dictionary attacks** a hacker systematically tries every word in a dictionary or a list of commonly used words as a password in an attempt to break into a password-protected account.
  - **Brute-force attack** the simplest and most commonly used way of gaining access to a password-protected site, brute-force attacks see an attacker using all possible combination of letters, numbers and symbols in the password space until they get it right.
  - **rainbow attacks** passwords in a computer system are not stored as plain text, but as hashed values (numerical values that uniquely identify data). A rainbow table is a large dictionary of precomputed hashes and the passwords from which they were calculated. Unlike a brute-force attack that has to calculate each hash, a rainbow attack compares the hash of a password with those stored in the rainbow table. When an attacker finds a match, they identify the password used to create the hash.
  - **Traffic interception** plain text or unencrypted passwords can be easily read by other humans and machines by intercepting communications. If you store a password in clear, readable text, anyone who has access to your account or device, whether authorized or unauthorized, can read it.
- **Advanced persistent threats** attackers also achieve infiltration through advanced persistent threats (APTs) a multi-phase, long term, stealthy and advanced operation against a specific target. For these reason, an individual attacker often lacks the skill set, resources or persistence to perform APTs. Due to the complexity and the skill required to carry out such attack, an APT is usually well-funded and typically targets organizations or nations for business or political reasons. The main purpose is to deploy customized malware on one or more of the target's systems and remain there undetected.

## Security Vulnerabilities
are any kind of software or hardware defect. A program written to take advantage of a known vulnerability is referred to as an exploit. A cybercriminal can use an exploit against a vulnerability to carry out an attack, the goal of which is to gain access to a system, the data it hosts or a specific resource.

## Hardware vulnerabilities
are most often the result of hardware design flaws. For example, the type of memory called RAM basically consist of lots of capacitors installed very close to one another. However, it was soon discovered that, due to their close proximity, changes applied to one of these capacitors could influence neighbor capacitors. Based on this design flaw, an exploit called Rowhammer was created. By repeatedly accessing (hammering) a row of memory, the Rowhammer exploits triggers electrical interferences that eventually corrupt the data stored inside the RAM.
Hardware vulnerabilities are specific to device models and are not generally exploited through random compromising attempts. While hardware exploits are more common in highly targeted attacks, traditional malware protection and good physical security are sufficient protection for the everyday user.

## Software Vulnerabilities
are usually introduced by errors in the operating system or application code.

## Categorizing Software Vulnerabilities
- **Buffer overflow** buffers are memory areas allocated to an application. A vulnerability occurs when data is written beyond the limits of a buffer. By changing data beyond the boundaries of a buffer, the application can access memory allocated to other processes. This can lead to a system crash or data compromise. Or provide escalation of privileges
- **Non-validated input** programs often require data input, but this incoming data could have malicious content, designed to force the program to behave in an unintended way. For example, consider a program that receives an image for processing. A malicious user could craft an image file with invalid image dimensions. The maliciously crafter dimensions could force the program to allocate buffers of incorrect and unexpected sizes
- **Race conditions** this vulnerability describes a situation where the output of an event depends on ordered or timed outputs. A race condition becomes a source of vulnerability when the required ordered or timed events do not occur in the correct order or at the proper time
- **Weaknesses in security practices** systems and sensitive data can be protected through techniques such as authentication, authorization and encryption. Developers should stick to using security techniques and libraries that have already been created, tested and verified and should not attempt to create their own security algorithms. These will only likely introduce new vulnerabilities
- **Access control problems** access control is the process of controlling who does what and ranges from managing physical access to equipment to dictating who has access to a resource, such as a file, and what they can do with it, such as read or change the file. Many security vulnerabilities are created by the improper use of access controls. Nearly all access controls and security practices can be overcome if an attacker has physical access to target equipment. For example, no matter the permission settings on a file, a hacker can bypass the operating system and read the data directly off the disk. Therefor, to protect the machine and the data it contains, physical access must be restricted, and encryption techniques must be used to protect data from being stolen or corrupted

## Software updates
The goal of software updates are to stay current and avoid exploitation of vulnerabilities. Microsoft, Apple and other operating system producers release patches and updates almost every day and applications such as web browsers, mobile apps and web servers are often update by the companies or organizations responsible for them. Despite the fact that organizations put a lot of effort into finding and patching software vulnerabilities, new vulnerabilities are discovered regularly. That's why some organizations use third party security researchers who specialize in finding vulnerabilities in software, or actually invest in their own penetration testing teams dedicated to search, find and patch software vulnerabilities before they can get exploited.

## The cybersecurity landscape
- **Cryptocurrency** cryptocurrency is digital money that can be used to buy goods and services, using strong encryption techniques to secure online transactions. Banks, governments and even companies like Microsoft and AT&T are very aware of this importance and are jumping on the cryptocurrency bandwagon
1. Cryptocurrency owners keep their money in encrypted, virtual 'wallets' When a transaction takes place between the owners of two digital wallets, the details are recorded in a decentralized, electronic ledger or blockchain system. This means it is carried out with a degree of anonymity and is self-managed, with no interference from third parties such as central banks or government entities.
2. Approximately every ten minutes, special computers collect data about the latest cryptocurrency transactions, turning them into mathematical puzzles to maintain confidentiality. These transactions are then verified through a technical and highly complex process known as 'mining'. This step typically involves an army of 'miners' working on high-end PCs to solve mathematical puzzles and authenticate transactions
3. once verified, the ledger is updated and electronically copied and disseminated worldwide to anyone belonging to the blockchain network, effectively completing a transaction
- **Cryptojacking** is an emerging threat that hides on a user's computer, mobile phone, tablet, laptop or server, using that machine's resources to 'mine' cryptocurrencies without the user's consent or knowledge. Many victims didn't know until it was too late.

## Protecting your data and privacy
### Protecting your computer devices
some tips to protect your device
1. **Turn the firewall on**: you should use at least one type of firewall (either a software firewall or a hardware firewall on a router) to protect your device from unauthorized access the firewall should be turned on and constantly updated to prevent hackers from accessing your personal or organization data.
2. **Install antivirus and antispyware** you should always download software from trusted websites. However, you should always use antivirus software to provide another layer of protection. This software, which often includes antispyware, is designed to scan your computer and incoming email for viruses and delete them. Keeping your software up to date will protect your computer from any new malicious software that emerges.
3. **Manage your operating system and browser** Hacker are always trying to take advantage of vulnerabilities that may exist in your operating system (Microsoft, browser, etc.). Therefore, to protect your computer and your data, you should set the security settings on your computer and browser to medium level or higher. You should also regularly update your computer's operating system, including your web browser, and download and install the latest software patches and security updates from the vendors.
4. **Set up password protection** all of your computing devices, including PCs, laptops, tablets and smartphones, should be password protected to prevent unauthorized access. Any sorted information, especially sensitive or confidential data, should be encrypted, You should only store necessary information on your mobile device, in case it is stole or lost. Remember, if any one of your devices is compromised, the criminals may be able to access all of your data through your cloud storage service provider (icloud, google drive)

## Wireless network security at home
Wireless networks allow Wi-Fi enabled devices, such as laptops and tablets, to connect to the network by way of a present network identified, known as the *service set identifier* (SSID). Although a wireless router can be configured so that it doesn't broadcast the SSID, this should not be considered adequate security for a wireless network. Hackers will be aware of the present SSID and default password. Therefore, these details should be changed to prevent intruders from entering your home wireless network. Furthermore, you should encrypt wireless communication by enabling wireless security and the WPA2 encryption feature on your wireless router. But be aware, even with WPA2 encryption enabled, a wireless network can still be vulnerable.

This vulnerability can be exploited by key reinstallation attacks kRACKs by intruders. Attackers break the encryption between a wireless router and a wireless device, giving them access to network data. This flaw affects all modern protected Wi-Fi networks. To prevent this:
- update all wireless capable devices asap
- use a wired connection
- use a trusted *virtual private network* VPN when accessing a wireless network
## Public Wi-Fi risks
you should always verify that your device isn't configured with file and media sharing and that it requires user authentication with encryption. You should also use an encrypted VPN service to prevent others from intercepting your information (known as 'eavesdropping') over a public wireless network. This service gives you secure access to the internet, by encrypting the connection between your device and the VPN server. Even if hackers intercept a data transmission in an encrypted VPN tunnel, they will not be able to decipher it

## Password security
use a strong password, do not repeat it across accounts. Use a passphrase instead of a password since is harder to crack by brute-force and is easy to remember

## Data maintenance
- **Encryption** is the process of converting information into a form in which unauthorized parties cannot read it. Only a trusted authorized person with the secret key or password can decrypt the data and access it in its original form. Note that the encryption itself does not prevent someone from intercepting the data. It can only prevent an unauthorized person from viewing or accessing the content. In fact, some criminals may decide to simply encrypt your data and make it unusable until you pay a ransom.
- **Backup** your data to prevent loss of irreplaceable data

## how to delete data permanently
1. overwrite it with 1's and 0's multiple times, using tools like SDelete (microsoft), Shred (linux), Secure empty thrash (Mac OS X).
2. physical destroy the hard drive or storage device. Many criminals take advantage of files thought to be impenetrable or irrecoverable

**Terms of service (TOS)** is a legally binding contract that governs the rules of the relationship between you, the service provider and others who use the service.
- data use policy: outlines how the service provider will collect, use and share your data.
- privacy settings: allow you to control who sees information about you and who can access your profile or account data.
- security policy: outlines what the company is doing to secure the data it obtains from you.

# Protecting your data and privacy

## factors to consider before you sign up
- have you read the TOS
- what are your rights regarding your data?
- can you request a copy of your data?
- what can the provider do with the data you upload?
- what happens to your data when you close your account?

## Safeguarding your online privacy
- **Two factor authentication** besides your username and password or personal identification number (PIN)m two factor authentication requires a second token to verify your identity. This may be a:
   - physical object such as a credit card, mobile phone.
   - biometric scan such as a fingerprint or facial and voice recognition.
   - verification code sent via SMS or email.
- **Open Authorization (OAuth)** is an open standard protocol that allows you to use your credentials to access third-party applications without exposing your password.
- **Social sharing** you decide to update your new job position on your social networks. When doing so, one of the sites asks you to update your profile information to ensure you receive the content that you really don't want to miss!

# Protecting the organization

## Security appliances
can be standalone devices like a router or software tools that are run on a network device. They fall into six general categories.
- **Routers** while are primarily used to interconnect various network segments together, they usually also provide basic traffic filtering capabilities. This information can help you define which computers from a given network segment can communicate with which network segments.
- **Firewalls** can look deeper into the network traffic itself and identify malicious behavior that has to be blocked. Firewalls can have sophisticated security policies applied to the traffic that is passing through them.
- **Intrusion prevention systems (IPS)** use a set of traffic signatures that match and block malicious traffic and attacks.
- **Virtual private network (VPN)** systems let remote employees use a secure encrypted tunnel from their mobile computer and securely connect back to the organization's network. VPN systems can also securely interconnect branch offices with the central office network.
- **Antimalware or antivirus** these systems use signatures or behavioral analysis of applications to identify and block malicious code from being executed.
- **Other security devices** include web and email security appliances, decryption devices, client access control servers and security management systems.

## Firewalls
In computer networking, a firewall is designed to control or filter which communication are allowed in and which are allowed out of a device or network. A firewall can be installed on a single computer with the purpose of protecting that one computer (host-based firewall) or it can be a standalone network device that protects an entire netwrok of computers and all of the host devices on that network (network-based firewall)

- **Network layer firewall** this filters communications based on source and destination IP addresses.
- **Transport layer firewall** filters communication based on source and destination data ports, as well as connection states.
- **Applicattion layer firewall** filters communications based on an application, program or service
- **Context aware layer firewall** filters communications based on the user, device, role, application type and threat profile.
- **Proxy server** filters web content requests like URLs, domain names and media types.
- **Reverse proxy server** placed in front of web servers, reverse proxy servers protect, hide, offload and distribute access to web servers.
- **Network address translation (NAT) firewall** this firewall hides or masquerades the private addresses of network hosts.
- **Host-based firewall** filters ports and system service calls on a single computer operating system

## Port scanning
in networking, each application running on a device is assigned an identifier called a port number. This port number is ued on both ends of the transmission so that the right data is passed to the correct application. Port scanning is a process of probing a computer, server or other network host for open ports. It can be used maliciously as a reconnaissance tool to identify the operating system and services running on a computer or host, or it can be used harmlessly by a network administrator to verify network security policies on the network.

## Intrusion Detection and Prevention systems
Intrusion detection systems (IDSs) and intrusion prevention system (IPSs) are security measures deployed on a network to detect and prevent malicious activities.
- **Intrusion detection systems (IDS)** can be either be a dedicated network device or one of several tools in a server, firewall or even a host computer operating system, such as windows or Linux, that scans data against a database of rules or attack signatures, looking for malicious traffic. If a match is detected, the ids will log the detection and create an alert for a network administrator. It will not take action and therefore it will not prevent attacks from happening. The job of the IDS is to detect, log and report. The scanning performed by the IDS slows down the network (known as latency). To prevent network delay, an IDS is usually placed offline, separate from regular network traffic. Data is copied or mirrored by a switch and then forwarded to the IDS for offline detection.
- **intrusion prevention system (IPS)** can block or deny traffic based on a positive rule or signature match. One of the most well-known IPS/IDS system is Snort. The commercial version of Snort is Cisco's sourcefire. Sourcefire can perform real-time traffic and port analysis, logging, content searching and matching, as well as detect probes attacks and execute port scans. it also integrate with other third-party tools for reporting, performance and log analysis.

## Real-time detection
many organizations today are unable to detect attacks until days or even months after they occur:
detecting attacks in real time requires actively scanning for attacks using firewall and IDS/IPS network devices. Next generation client and server malware detection with connections to online global threat centers must also be used. Today, active scanning devices and software must detect network anomalies using context-based analysis and behavior detection.
DDoS is one of the biggest attack threats requiring real-time detection and response. For many organizations, regularly occurring DDoS attacks cripple internet servers and network availability. These attacks are extremely difficult to defend against because the attacks originate from hundreds, even thousands, of zombie hosts, and the attacks appear as legitimate traffic

## Protecting against malware
one way of defending against zero-day attacks and advanced persistent threats (APTs) is to use an enterprise-level advanced malware detection solution, like Cisco's advanced malware protection (AMP) threat grid. This is client/server software that can be deployed on host endpoints, as a standalone server or on other network security devices. It analyzes millions of files and correlates them against hundreds of millions of other analyzed malware artifacts for behaviors that reveal an APT. This approach provides a global view of malware attacks, campaigns and their distribution.

## Security best practices
Many national and professional organizations have published list of security best practices. Some of the most helpful guidelines are found in organizational repositories such as the National institute of standards and technology (NIST) Computer security resources center.
- **Perform a risk assessment** knowing and understanding the value of what you are protecting will help to justify security expenditures
- **Create a security policy** create a policy that clearly outlines the organization's rules, job roles, and responsibilities and expectations for employees.
- **Physical security measures** restrict access to networking closets and server locations, as well as fire suppression
- **Human resoureces security measures** background check should be completed for all employees
- **perform and test backups** back up information regularly and test data recovery from backups.
- **Maintain security patches and updates** regularly update server, client and network device operating systems and programs.
- **Employ access controls** configure user roles and privilege levels as well as strong user authentication.
- **Regularly test incident response** employ an incident response team and test emergency response scenarios.
- **Implement a network monitoring, analytics and management tool** choose a security monitoring solution that integrates with other technologies.
- **Implement network security devices** use next generation routers, firewalls and other security appliances.
- **Implement a comprehensive endpoint security solution** use enterprise level anti-malware and antivirus software
- **educate users** provide training to employees in security procedures. One of the most widely known and respected organizations for cybersecurity training is the SANS institute.
- **Encrypt data** encrypt all sensitive organizational data, including email.

## Behavior approach to cybersecurity
behavior-based security is a form of threat detection that involves capturing and analyzing the flow of communication between a user on the local network and a local or remote destination. Any changes in normal patterns of behavior are regarded as anomalies, and may indicate an attack.
two behavior-based detection tools:
- **honeypots** is a behavior-based detection tool that lures the attacker in by appealing to their predicament pattern of malicious behavior. Once the attacker is inside the honeypot, the network administrator can capture, log and analyze their behavior so that they can build a better defense
- **Cisco's cyber threat defense solution architecture** this security architecture uses behavior-based detection and indicators to provide greater visibility, context and control. The aim is to know who is carrying out the attack, what type of attack they are performing and where, when and how the attack is taking place. This security architecture uses many security technologies to achieve this goal.

## netflow
netflow technology is used to gather information about data flowing through a network, including who and what devices are in the network, and then and how users and devices access the network. netflow is an important component in behavior-based detection and analysis. switches, routers, and firewalls equipped with netflow can report information about data entering, leaving and traveling through the network. This information is sent to netflow collection that collect, store and analyze netflow data, which can be used to establish baseline behaviors on more than 90 attributes, such as source and destination IP address

## Penetration testing
penetration testing, is commonly known as pen testing, is the act of assessing a computer system, network or organization for security vulnerabilities. A pen test seeks to breach systems, people, processes and code to uncover vulnerabilities which could be exploited. This information is then used to improve the system's defense to ensure that it is better able to withstand cyber attacks in the future. There is five steps for the process
1. **Planning** the pen tester gathers as much information as possible about a target system or network, its potential vulnerabilities and exploits to use against it. This involves conducting passive or active reconnaissance (footprinting) and vulnerability research.
2. **Scanning** the pen tester carries out active reconnaissance to probe a target system or network and identify potential weaknesses which, if exploited, could give an attacker access. Active reconnaissance may include:
  - port scanning to identify potential access points into a target system
  - vulnerability scanning to identify potential exploitable vulnerabilities of a particular target
  - establishing an active connection to a target (enumeration) to identify the user account, system account and admin account.
3. **Gaining access** the pen tester will attempt to gain access to a target system and sniff network traffic, using various methods to exploit the system including:
  - launching an exploit with a payload onto the system
  - breaching physical barriers to assets
  - social engineering
  - exploiting website vulnerabilities
  - exploiting software and hardware vulnerabilities or misconfigurations
  - breaching access controls security
  - cracking weak encrypted Wi-Fi
4. **Maintaining access** the pen tester will maintain access to the target or find out what data and systems are vulnerable to exploitation. It is important that they remain undetected, typically using backdoors, Trojan horses, rootkits and other covert channels to hide their presence. When this infrastructure is in place, the pen tester will then proceed to gather the data that they consider valuable.
5. **Analysis and reporting** the pen tester will provide feedback via a report that recommends updates to products, policies and training to improve an organization's security.

## Impact reduction
while most organizations today are aware of common security threats and put considerable effort into preventing them, no set of security practices is foolproof. Therefore, organizations must be prepared to contain the damage if a security breach occurs. And they must act fast. Actions organizations should take when security breach is identified.
- **Communicate the issue** communication creates transparency, which is critial in this type of istuation. Internally, all employees should be informed and clear call to action communicated. Externally, all clients should be informed through direct communication and official announcements.
- **Be sincere and accountable** Respond to the breach in an honest and genuine way, taking responsibility where the organization is at fault.
- **Provide the details** Be open and explain why the breach took place and what information was compromised. Organizations are generally expected to take care of any client cost associated with identify theft services required as a result of a security breach.
- **Find the cause** Take steps to understand what caused and facilitated the breach. This may involve hiring forensics experts to research and find out the details.
- **Apply lessons learned** make sure that any lessons learned from forensic investigations are applied to prevent similar breaches from happening in the future.
- **Check, and check again** attackers will often attempt to leave a backdoor to facilitate future breaches. To prevent this form happening, make sure that all systems are clean, no backdoors are installed and nothing else has been compromised
- **Educate** raise awareness, and educate employees, partners and clients on how to prevent future breaches.

## Risk management
Risk management is the formal process of continuously identifying and assessing risk in an effort to reduce the impact of threats and vulnerabilities. you cannot eliminate risk completely but you can determine acceptable levels by weighing up the impact of threat with the cost of implementing controls to mitigate it. The cost of a control should never be more than the value of the asset you are protecting

- **Frame risk** identify the threats that increase risk, threats may include processes, products, attacks, potential failure or disruption of services, negative perception of an organization's reputation, potential legal liability or loss of intellectual property.
- **Assess the risk** determine the severity that each threat poses. For example. Some threats may have the potential to bring an entire organization to a standstill, while other threats may be only minor inconveniences. Risk can be prioritized by assessing financial impact (a quantitative analysis) or scaled impact on an organization's operation (a qualitative analysis)
- **Respond to risk** Develop an action plan to reduce overall organization risk exposure, detailing where risk can be eliminated, mitigated, transferred or accepted.
- **Monitor the risk** Continuously review any risk reduced through elimination, mitigation or transfer actions, Remember, not all risk can be elminated, so you will need to closely monitor any threats that have been accepted.

## Security playbook
One of the best ways to prepare for a security breach is to prevent it. Organizations should provide guidance on:
- how to identify the cybersecurity risk to systems, assets, data and capabilities
- the implementation of safeguards and personnel training
- a flexible response plan that minimizes the impact and damage in the events of a security breach
- security measures and processes that need to be put in place in the aftermath of a security breach.

all this information should be compiled in a security playbook, this is a collection of repeatable queries or reports that outline a standardized process for incident detection and response. Ideally, a security playbook should"
- highlight how to identify and automate the response to common threats such as the detection of malware-indected machines, supicious network activity or irregular authentication attempts.
- describe and clearly define inbound and outbound traffic.
- provide summary information including trends, statics, and counts.
- provide usable and quick access to key statics and metrics.
- correlate events across all relevant data sources.

## Tools for incident detection and prevention
- **Security information and event management (SIEM)** system collects and analyzes security alerts, logs and other real-time and historical data from security devices on the network to facilitate early detection of cyber attacks.
- **Data loss prevention (DLP)** system is designed to stop sensitive data from being stolen from or escaping a network. it monitors and protects data in three different states: data in use (data being accessed by a user), data in motion (data traveling through the network) and data at rest (data stored in a computer network or device)

## Cisco's ISE and TrustSec

Cisco identity services Engine (ISE) and TrustSec enforce user access to network resources by creating role-based access control policies

# Legal and ethical issues

## Personal legal issues
At work or home, you may have the opportunity and skills to hack another person's computer or network. but here is an old sayin, 'just because you can does not mean you should.' Most hacks leave tracks, which can be traced back to you.
Cybersecurity professionals develop many skills, which can be used positively or illegally. There is always a huge demand for those who choose to put their cyber skills to good use within legal bounds.

## Corporate legal issues
Most countries have cybersecurity laws in place, which businesses and organizations must abide by. In some cases, if you break cybersecurity laws while doing your job, the organization may be punished and you could lose your job. In other cases, you could be prosecuted, fined and possibly sentenced. In general, if you are unsure whether an action or behavior might be illegal, assume that it is illegal and do not do it. Always check with the legal or HR department in the organization.

## International law and cybersecurity
International cybersecurity law is a constantly evolving field. Cyber attacks take place in cyberspace, an electronic space created, maintained and owned by both the public and private entities. There are no traditional geographic boundaries in cyberspace. To further complicate issues, it is much easier to mask the source of a attack in cyberwarfare than in conventional warfare. The global society is still debating how best to deal with cyberspace. Country practice, opinion juris (a sense on behalf of a country that is bound to the law in question) and any treaties drafter will shape international cybersecurity law.

## Ethical issues in cybersecurity
Ask yourself the following questions to help decide on the best course of action
- is it legal
- does your action comply with your organization policy?
- will your action be favorable for your organization and its stakeholders?
- would it be okay if everyone in your organization took this action?
- would the outcome of your action present your organization in a positive light in a news headline?

## Most common certifications
- **Cisco certified support technician (CCST) cybersecurity** this is an entry-level certification for newcomers who are preparing to start their career in the cybersecurity field. it is aimed at high school and early college students as well as those interested in a career change. This certificate does not expire or require periodic recertification.
- **CompTIA Security+** this is an entry-level security certification that meets the U.S. Department of defense directive 8570.01-M requirements, which is an important item for anyone looking to work in IT security for the federal government.
- **EC Council certified ethical hacker (CEH)** This certification tests your understanding and knowledge of how to look for weaknesses and vulnerabilities in target systems using the same knowledge and tools as a malicious hacker but in a lawful and legitimate manner.
- **ISC2 Certified Information Systems Security Professional (CISSP)** this is the most recognizable and popular security certification. In order to take the exam, you need to have at least five years of relevant industry experience.
- **Cisco Certified CyberOps Associate** this certification validates the skills required of associate-level cybersecurity analyst within security operations centers.
