---
layout: default
---

# Cybersecurity Projects

This site is used to store all of my Cybersecurity projects, describe each of them, and what I learned from the project. This will be updated periodically as I begin new projects, reach milestones in current projects, or reach what I consider to be completion on current projects. Projects are added to the lists below based on when these different timepoints are reached. It should be noted that this does not include projects that I complete as part of my current role as a Network Administrator but rather are done on my own time with the goal of learning outside of my current job requirements to improve my skills in the field of Cybersecurity. 

* * *

## Current projects
1. SIEM System
2. Google Cybersecurity Certification

## Completed projects
1. Software Development Security Policy
2. Reverse Engineering for Vulnerabilities

* * *

## Description of Projects

### Software Development Security Policy
This policy was completed as part of a project for a Secure Coding course that I completed in my coursework with SNHU. This project included both the written policy and a presentation on the policy to describe it to a diverse audience. This policy included describing 10 core security principles for secure coding, determining 10 secure coding standards that should be prioritized, policies for encryption and the Triple A framework (Authentication, Authorization, and Accounting), and a risk assessment on each coding standard. The full write up for this project can be found here: https://github.com/cberger32/SNHU-CS405

### Reverse Engineering for Vulnerabilities
This was completed as part of a project for a Reverse Engineering course that I completed in my coursework with SNHU. 

### SIEM System
A SIEM system was setup in a virtual environment using VirtualBox. The SIEM being used is Wazuh with the server components being hosted in Docker containers on an Ubuntu server and the agent being installed on a Windows 11 virtual machine and a Kali Linux virtual machine. Wazuh was chosen because it is open source with numerous tutorials on the initial setup of the software. A Windows virtual machine was chosen because Windows is the most common OS used in Enterprise organizations for end users. This will allow me to become familiar with the various logs that will be sent from the agent to the Wazuh server. A Kali Linux virtual machine was chosen so that it can be used to simulate different attacks that may be seen in the wild on a Windows machine. Simulating these attacks and then identifying the corresponding logs in Wazuh will allow me to the create rules and alerts that would notify me if a similar attack were to occur elsewhere in the environment. This has also helped me familiarize myself with Linux systems, virtualization, and Docker. 
Completing the initial setup of each of these virtual machines and Wazuh taught me a lot. I learned how to deploy new virtual machines using VirtualBox, how to make adjustments to the machines like increasing storage space or changing RAM/CPU allocations, and also how to create a network specifically for the virtual machines. I also learned a lot of troubleshooting skills regarding virtual machines and Docker containers. The troubleshooting ranged from learning how to get each of the virtual machines to communicate with each other to troubleshooting various errors I was receiving with Docker containers when trying to setup Wazuh. A new network was created so that they can communicate with each other and with the internet, but not with any other devices on my personal home network, not even the computer that I am running all of these virtual machines on. This creates a safe space for me to learn new topics and techniques. Following the deployment of Wazuh on my Ubuntu virtual machine through the use of containers and Docker Compose, I began exploring the dashboard to see the various components that were present. During this I discovered how to install the agent on the Windows machine in my homelab and connect it to the Wazuh server. I also learned how to deploy the agent to a Linux device so that once I will be able to see the logs of when simulating various attacks. 

### Google Cybersecurity Certification
The Google Cybersecurity Certification is being pursued because of the inclusion of labs and hands-on practice. More info will be added in the future as I progress through the course. If desired, the CompTIA Security+ certification may be pursued once this is completed. 


Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
