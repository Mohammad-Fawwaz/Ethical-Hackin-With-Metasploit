# Ethical Hacking With Metasploit

## Objective

To demonstrate the identification, exploitation, and mitigation of security vulnerabilities in a controlled environment using the industry-standard tools such as Nmap, Metasploit, and John the Ripper. The project aims to highlight key stages of the ethical hacking process, including information gathering, vulnerability assessment, exploitation, and post-exploitation activities, while ensuring adherence to ethical hacking standards and legal frameworks.

### Skills Learned

- Advanced understanding of Metasploit Framework and practical application.
- Search for open ports and trying to gain access by understanding the port versions.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Nmap: Network scanning and reconnaissance to map open ports and identify potential vulnerabilities.
- Metasploit: Exploitation of identified vulnerabilities and post-exploitation to assess system defenses.
- John the Ripper: Password cracking and testing to highlight weak authentication mechanisms.
- Kali Linux is a specialized, open-source penetration testing and ethical hacking operating system equipped with numerous security tools.
- Metasploitable is a vulnerable virtual machine designed for testing and practicing exploitation techniques using tools like Metasploit in a controlled environment.

## Steps
- Power up kali linux and metasploitable
- open terminal in kali linux
- type msfconsole to get into metasploit framework
- ![image](https://github.com/user-attachments/assets/83730743-349e-48a8-8fb8-e4c6cb5e10b8)
- know the ip address of your network and scan the network using nmap
- ![image](https://github.com/user-attachments/assets/2f3e474a-ceb0-4f34-95ff-2a04ed718571)
- now run a nmap on the ip 192.168.160.130 as it seems to have many open ports
- ![image](https://github.com/user-attachments/assets/cd94d0af-93ce-4cc8-9fbc-e162884cd343)
- ![image](https://github.com/user-attachments/assets/b3da5c94-7474-4a39-9914-8b775432e514)
- ![image](https://github.com/user-attachments/assets/8b2da781-f191-4afa-b24e-bb6d4feb14b4)
- there are many open ports and lets go with data base postgreSQL which is on 5432/tcp port because there are many known vulnerabilities
- metasploit allows you to search vulnerability types in the auxilary
- ![image](https://github.com/user-attachments/assets/74ea0850-aad1-4cd2-8a08-d7e200724c09)
- here let us use auxiliary/scanner/postgres/postgres_login and can bruteforce login
- ![image](https://github.com/user-attachments/assets/0e3fc9a3-ab2d-4e7a-99a3-4a8514321528)
- u need to set RHosts ipaddress of target machine and can type run
- ![image](https://github.com/user-attachments/assets/23fe1cae-da2f-4851-9e36-bf5bd3bf429d)
- now we are certain that u can login using postgres:postgres as username and password







