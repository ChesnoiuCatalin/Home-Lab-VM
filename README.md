# Home-Lab-VM

A home lab for ethical hacking can be set up using a virtual machine (VM) such as VirtualBox. The lab can be used to simulate a real-world environment, allowing users to practice their ethical hacking skills in a safe and secure environment. Here is how a basic home lab for ethical hacking can be set up using VirtualBox:

1. Download and install the latest version of VirtualBox.

Oracle VM Virtual Box : https://www.virtualbox.org/wiki/Downloads

2. Create two virtual machines, one for the attacker and one for the target.

3. Install the same operating system on both machines, such as Windows or Linux.

4. Set up the networking for both machines to allow for communication between the two.

5. Install the necessary tools for ethical hacking on the attacker machine.

6. Install vulnerable software or services on the target machine, such as FTP or web servers.

7. Begin testing your ethical hacking skills on the target machine.

8. Monitor the target machine for any suspicious activity or suspicious connections.

9. Document the results of your tests and any findings.

10. Use the results of your tests to improve your ethical hacking skills.



# The advantages of using a local Home Lab are :

1. Cost-Effective: One of the main benefits of using a local VM home lab for ethical hacking is its cost-effectiveness. It is much cheaper to set up and maintain a home lab than to purchase and maintain expensive hardware and software.

2. Flexibility: With a home lab, a hacker can easily customize the environment to their exact needs. This makes it much easier to learn different techniques and develop new skills.

3. Security: By keeping the lab local, the hacker can keep their data and activities secure from outside intrusions and vulnerabilities.

4. Accessibility: A local VM home lab can be accessed from anywhere with an internet connection, making it ideal for those who travel or work from home.

5. Scalability: The lab can easily be expanded as needed to accommodate more machines or other components. This allows for the flexibility to experiment with different techniques and technologies.

# My Personal Home Lab : 

![Screenshot_21](https://user-images.githubusercontent.com/56380723/208121213-8d87eb81-b80f-4777-a77d-ca062104a96f.png)

VM attacker :

![Screenshot_21](https://user-images.githubusercontent.com/56380723/208122579-09f6b6e5-0f97-4947-adc3-76c1e92ce3ca.png)

Debian-based Linux :

Kali Linux : https://www.kali.org/get-kali/

Kali Linux is a Debian-based Linux distribution designed for digital forensics, penetration testing, and security auditing. It includes a large collection of security-related tools, such as port scanners, password crackers, and wireless analysis tools, that can be used to assess the security of network systems. It is maintained and funded by Offensive Security Ltd.

Parrot OS : https://www.parrotsec.org/download/

Parrot OS is a Linux distribution based on Debian and focused on security, privacy, and development. It comes with a variety of tools designed for ethical hacking, penetration testing, computer forensics, reverse engineering, and privacy protection. It is available in both 32 and 64-bit versions, and is designed to be lightweight and easy to use.

Ziion OS : https://www.ziion.org/

Ziion OS is a decentralized, smart contract audit platform that provides users with the tools and resources they need to identify, investigate, and report on the security of their smart contracts. Ziion OS offers a range of features, such as automated smart contract scanning, real-time monitoring, and an interactive dashboard. With these features, users can easily identify vulnerabilities and potential risks in their smart contract code, allowing them to take action and protect their data.

Dragon OS : https://sourceforge.net/projects/dragonos-focal/

Dragon OS is an open-source radio signal processing software designed to provide an intuitive and efficient workflow for manipulating and analyzing radio signals. It is built on the Python programming language and utilizes the NumPy and SciPy libraries to provide a comprehensive suite of signal processing tools. Dragon OS is capable of handling a wide variety of signal types such as FM, AM, SSB, and CW. It also offers a range of features such as power spectrum plotting, frequency estimation, signal modulation, and signal noise reduction.

OSINT TraceLab : https://www.tracelabs.org/initiatives/osint-vm

OSINT Trace Lab is an open source intelligence (OSINT) tool designed to help security professionals and researchers trace malicious actors and find valuable evidence for investigations. It provides an easy-to-use graphical user interface, allowing users to quickly and easily query multiple online data sources, such as social networks, WHOIS records, domain registries, and more. It also includes powerful analytics and visualization tools to help users uncover valuable insights.

Arch-based Linux :

Black Arch : https://blackarch.org/downloads.html

BlackArch Linux is an open-source Linux distribution for penetration testing and security research. It is based on Arch Linux, and is specifically designed for security professionals and researchers. It provides over 2000 security tools organized into categories, such as vulnerability analysis, wireless attacks, web applications, exploitation, stress testing, forensics, and more. BlackArch Linux is available as an ISO image and can be installed on a system or run as a live environment.

VM Targets :

![Screenshot_21 (1)](https://user-images.githubusercontent.com/56380723/208122588-8009e811-b11d-4641-b4db-ee882d901126.png)



windows 7 : https://www.softlay.com/downloads/windows-7-ultimate

Windows 10 : https://www.microsoft.com/ro-ro/software-download/windows10ISO

Windows Server 2019 : https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019

Android ISO : https://techrechard.com/download-android-iso-image-file-for-virtualbox-vmware/

OWASP Broken Web Application : https://sourceforge.net/projects/owaspbwa/

ShellShock : https://www.pentesterlab.com/exercises/cve-2014-6271/course

Metasploitable : https://sourceforge.net/projects/metasploitable/

Web Security Dojo : https://sourceforge.net/projects/websecuritydojo/

# Wath I learn in the process

Installed, configured and maintained Oracle VM VirtualBox in ethical hacking operations. And conducted penetration testing and vulnerability assessments using virtual machines.

I became familiar with different operating systems like Windows, Linux (Debian-based and Arch-based), and Android.

Knowledgeable about OSINT best practices and protocols, such as the use of privacy settings, data protection, and online forensics. I use tools like : Maltego, Shodan, Google Dorks, TheHarvester, OpenVAS

Ability to analyze and interpret network traffic using packet sniffers, such as Wireshark.

Ability to quickly identify open ports and services using tools such as nmap, Nessus, and other port scanners.

Network scanning using tools such as NMAP and Nessus can help identify potential vulnerabilities in a system. Once identified, these vulnerabilities can be patched or addressed to protect the system from potential security threats.

Knowledgeable in Active Directory, group policies, and network protocols. To gain a better understanding of Active Directory, I use a Windows Server 2019 and a Windows 10 machine to learn how to administer a local network and how to apply this knowledge in a penetration test as an "attacker".

I practice various attacks against Windows operating systems, such as EternalBlue and DoublePulsar, on both Windows 7 and Windows 10 machines.

I use frameworks like Metasploit, TheFatRat, Evil-Droid (for Android) and REMCOS (Windows RAT) to exploit the vulnerabilities of target machines by generating and setting payloads and malicious packets to launch attacks.

I have learned how to embed malicious code into apps, images and other file types.

Experienced in configuring and troubleshooting Apache Tomcat servers for web applications.

For training on web application vulnerability and bug bounties, I use Metasploitable, ShellShock, Web Security Dojo, and OWASP Broken Web Application machine. Thanks to these virtual machines, I was able to discover how to exploit the following vulnerabilities: 

      * HTML Injection
      * SQL Injection
      * Cross-site scripting (XSS)
      * Man in the Midel Attack
      * Broken Access Control
      * Server-side Request Forgery
      * Identification and Authentication Failures
      * Sensitive Data Exposure
