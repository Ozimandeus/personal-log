# # Project Brief

O.Sawtell - Feb 2019

## Project Definition

Linux Desktop use on on some company systems is required to enabled better hardware resource utilization and allow for test orientated software to be utilized in the most efficent way.

## Outline Business Case

We currently have only Windows base-metal machines. Meaning that where we have a need to utilize Linux, we have to use Virtual Machines. Whilst this is functionally the same. A Virtual Machine can only utilize 50% of the resources on the host machine (and often less). This means that the speed of the system is far slower than achievable. In short, we are only leveraging 50% of the available hardware resources available to us. This is inefficient, wasteful and leads to lower productivity.

In addition, to help keep costs low, our automation system must be based on Linux and utilize docker. Whilst docker is available on Windows, the Linux version is a superior product. This is because docker leverages features of the Linux kernel directly. Whereas the Windows version relies on a less robust virtualization solution (Hyper-V). Additional benefits of Linux utilization are:

* Ubuntu Linux is free (no ongoing license or support cost).
* Open Source (and free) products available for most day-to-day and management tasks.
* Security - Linux is more secure than Windows 10:

  * Root password - prevents accidental installation of malware or viruses (Phishing attacks far less effective).
  * Virus authors tend to target mono-cultures (Outlook, Windows, etc) - Linux is (by nature) multi-culture.
  * Linus law - "given enough eyeballs, all bugs are shallow" instead of 'security through obscurity', flaws - are found by the community and fixes found and distributed more rapidly than any one single company can do.
  * Use of IP-tables.

* Security & Privacy - Linux distros do not routinely collect user data.
* Security - less virus and malware, and if normal repos are used, less risk of virus or malware infection.
* Higher performance from hardware assets, the Linux footprint is significantly lower than Windows 10 thereby more processing power can be leveraged for applications that we use. Looking ahead, we will be able to sweat our hardware assets longer if Linux is used, over an ever growing Windows 10.
* Reliability - In Linux all applications are self contained, therefore if the application crashes, the OS cannot be effected.
* Update control - Linux allows you complete control of updates, without the need for management software (no forced updates by OS vendor).

## Project Objectives

* Install x1 Linux Base-metal machine, in order to prove concept (Linux controlled by Windows Domain).
* Install Latest version of Ubuntu and configure as a test environment machine.
* Use machine to prove concept that Linux machines can be controlled via policy/active directory/samba.
* Utilize machine as a Test server, from which to run test automation scripts.
* Machine will form the basis of a true 'test environment' - allowing us to test in isolation from dev and qa sections.

### Timescale

* Proof of concept delivered Before end of first quarter 2019.
* If successful, specific machines (on case by case basis) to be made Linux base-metal be end of second quarter 2019.

### Capital Cost

* Zero - test machine is a machine currently not in use.
* No ongoing cost for hardware planned.

### Operational Cost

* if project moves from proof of concept, to production, then servers in DataVita Farm, may prove necessary to support testing scope as it increases.
* Time to setup - approx two man weeks work initially.
* Ongoing costs - TBA (based on if proof of concept is a success).

### In Scope

* Installation and build authoring of Linux Images.
* Installation of builds onto specific machines.
* Use of Latest Ubuntu Linux (at time of writing 18.10).
* Use of any open source tools required to support test automation.
* Use of any open source tools required to support day-to-day use of Linux.
* Testing of Windows Domain control of Linux machine.
* Use of Machine for test automation tasks.
* Exploration of third party tools that may assist with Windows Domain control (e.g. Samba, Centrify, etc).
* Explore if developers can gain productivity benefits if working within Linux.

### Constraints

* must comply with Cyber-security fundamentals.
* must be manageable from within Windows Farm.
* Test team to be used to help create the system.
* Test team to be used to facilitate the installation of test automation system.

### Not In Scope

* Other Linux Distros

### Risks

* Time needed by Devops may make it difficult to achieve all goals by end of March.

## Author

Oli Sawtell

Test Manager

Phone: 07741 644540

E-mail:  osawtell@airpoint.com

SkypeForBusiness: osawtell@airpoint.com

Website:  www.airpoint.net