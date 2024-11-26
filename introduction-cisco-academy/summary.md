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

**internet of things (IoT) and big data**: IoT is a large network of physical objects, such as sensors, software and other equipment. All of these things are connected to the internet, with the ability to collect and share data. And given that storage options are expanding through the cloud and virtualization, it's no surprise that the emerge of IoT has led to an exponential growth in data, creaing a new area of intereset in technology and business called 'Big Data'.

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
- **Worms**: replicates itself in order to spread from one computer to another. Unlike a virus, which requires a host program to run, worms can run y themselves. Other than the initial infection of the host, they do not require user participation and can spread very quickly over the network. Have a similar patten: exploit system vulnerabilities, they have a way to propagate themselves, and they all contain malicious code (payload) to cause damage to computer systems or networks. Worms are responsible for some of the most devastating attacks on the internet. In 2001, the Code red worm had infected over 300.000 servers in just 19 hours.

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
- denial-of-service (DoS): attacks are a type of network attack that is relatively simple to carry out, even by an unskilled attacker. A DoS attack result in some sort of interruption of network service to users, devices or applications.
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
  - **
