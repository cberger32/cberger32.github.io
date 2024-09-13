---
layout: default
---

This page is used to store my portfolio of Cybersecurity projects, describe each of them, and what I learned from the project. This will be updated periodically as I begin new projects, reach milestones in current projects, or reach what I consider to be completion on current projects. Projects are added to the lists below based on when these different timepoints are reached. It should be noted that this does not include projects that I complete as part of my current role as a Network Administrator but rather are done on my own time with the goal of learning outside of my current job requirements to improve my skills in the field of Cybersecurity. 

* * *

## Current projects
1. SIEM Lab
2. Google Cybersecurity Certification

## Completed projects
1. Software Development Security Policy
2. Reverse Engineering for Vulnerabilities

* * *

## Description of Projects

### Software Development Security Policy
* This policy was completed as part of a project for a Secure Coding course that I completed in my coursework with SNHU. This project included both the written policy and a presentation on the policy to describe it to a diverse audience. This policy included describing 10 core security principles for secure coding, determining 10 secure coding standards that should be prioritized, policies for encryption and the Triple A framework (Authentication, Authorization, and Accounting), and a risk assessment on each coding standard. The full write up for this project can be found [here](https://github.com/cberger32/SNHU-CS405).

### Reverse Engineering for Vulnerabilities
* This was completed as part of a project for a Reverse Engineering course that I completed in my coursework with SNHU. This project started with a working executable, converted it to binary, and then studied this to determine how the program functioned. The programs that were used to study this were GDB and a hex editor. Using both of these tools I was able to determine what variables and constants were present in the program and also the details of how the program functioned. Using GDB, I was able to take the binary file of the program, convert it into Assembly code, and then convert that Assembly code into C++. Once I had reverse engineered the binary file from Assembly code to C++, I then began to hunt for vulnerabilities. During my search I was able to uncover vulnerabilities regarding input validation, storage of PII as global variables, and poor error handling, among other security vulnerabilites.
  Completing this project took me through the process of taking a working executable, breaking it down into Assembly code, and then building a program in C++ with the same functionality. I gained experience hunting for vulnerabilities and determining how to fix them. I also started learning the details of working with machine code while gaining experience working with files in the linux command line. 

### SIEM Lab
* A SIEM system was setup in a virtual environment using VirtualBox. The SIEM being used is Wazuh with the server components being hosted in Docker containers on an Ubuntu server and the agent being installed on a Windows 11 virtual machine and a Kali Linux virtual machine. Wazuh was chosen because it is open source with numerous tutorials on the initial setup of the software. A Windows virtual machine was chosen because Windows is the most common OS used in Enterprise organizations for end users. This will allow me to become familiar with the various logs that will be sent from the agent to the Wazuh server. A Kali Linux virtual machine was chosen so that it can be used to simulate different attacks that may be seen in the wild on a Windows machine. Simulating these attacks and then identifying the corresponding logs in Wazuh will allow me to the create rules and alerts that would notify me if a similar attack were to occur elsewhere in the environment. This has also helped me familiarize myself with Linux systems, virtualization, and Docker. 
Completing the initial setup of each of these virtual machines and Wazuh taught me a lot. I learned how to deploy new virtual machines using VirtualBox, how to make adjustments to the machines like increasing storage space or changing RAM/CPU allocations, and also how to create a network specifically for the virtual machines. I also learned a lot of troubleshooting skills regarding virtual machines and Docker containers. The troubleshooting ranged from learning how to get each of the virtual machines to communicate with each other to troubleshooting various errors I was receiving with Docker containers when trying to setup Wazuh. A new network was created so that they can communicate with each other and with the internet, but not with any other devices on my personal home network, not even the computer that I am running all of these virtual machines on. This creates a safe space for me to learn new topics and techniques. Following the deployment of Wazuh on my Ubuntu virtual machine through the use of containers and Docker Compose, I began exploring the dashboard to see the various components that were present. During this I discovered how to install the agent on the Windows machine in my homelab and connect it to the Wazuh server. I also learned how to deploy the agent to a Linux device so that once I will be able to see the logs of when simulating various attacks. 

### Google Cybersecurity Certification
* The Google Cybersecurity Certification is being pursued because of the inclusion of labs and hands-on practice. More info will be added in the future as I progress through the course. If desired, the CompTIA Security+ certification may be pursued once this is completed. 
