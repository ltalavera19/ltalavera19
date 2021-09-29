# Chapter 03 - Review Questions

1) What is the term for the industry standard file format that is used to install a Linux distro?

  a. ISO (CORRET)

  b. ZIP

  c. Disk-ISO

  d. Distro

2) What is currently the most common Linux install media type?

  a. CD-ROMs

  b. Network based installs

  c. USB (CORRECT)

  d. Thunderbolt

3) What is the name of recommended tool used to create bootable Linux install media?

  a. Pendrive Linux

  b. etcher.io (CORRECT)

  c. UNetbootin

  d. Image Magick

4) What is the technology that is inserted between ring 1 and ring 0 that enables virtualization?

A hypervisor

5) The operating system that the hypervisor resides on is called the _________ system?

the HOST system

6) Hosted or desktop virtualization is called what type of hypervisor?

A Type II Hypervisor

7) Bare Metal or Native Virtualization is called what type of hypervisor?

A Type I Hypervisor

8) Each Linux installation distro provides a mechanism to compare what you downloaded with what you expected to download, what is that called?

  a. mount point

  b. checksum (CORRECT)

  c. receipt

  d. mdsum

9) What is the name of the driver package you can install in VirtualBox in order to enable features such as shared clipboard, larger screen resolution, and mouse pointer integration?

  a. Kernel modules

  b. Kernel drivers

  c. VirtualBox extensions (CORRECT)

  d. ISO extensions

  I though it would be VitualBox Guest Additions

10) What is the name for a Linux distribution that runs in memory?

  a. Rapid CD

  b. Live ISO (CORRECT)

  c. Install Disk

  d. Trick question

11) What feature doesn't dpkg handle/support?
  a. Removing software

  b. Installing dependencies (CORRECT)

  c. Versioning

  d. Author Information

12) What is the APT command to add an additional software repository in Ubuntu/Debian, named: `ppa:linux-libre/ppa`, to your APT system?

  a. `sudo add-repository ppa:linux-libre/ppa`

  b. `sudo add-apt-repository ppa:linux-libre/ppa` (CORRECT)

  c. `sudo apt-add-repository ppa:linux-libre/ppa`

  d. `sudo apt-add ppa:linux-libre/ppa`  

13) Which distro(s) supports the .deb package?

  a. Ubuntu only

  b. Debian Family (CORRECT)

  c. Debian and Red Hat

  d. None of the above

14) Which distro(s) supports the RPM package?

  a. CentOS only

  b. Red Hat Family (CORRECT)

  c. Debian and Red Hat

  d. None of the above

15) We talked about using GCC to compile and install software, what was the other language/package manager discussed in the chapter?

  a. G++

  b. APT

  c. Python (CORRECT)

  d. None of the above

16) Describe the purpose of VirtualBox Guest Additions?

The purpose of the VirtualBox Guest Addtions is for them to be installed inside of a virtual machine after the guest operating system has been installed. They are made up of device drivers and system applications that have the ability to optimize the guest operating system for better performance and usability.

17) What is the RPM command to install a package from the command line?

  a. `rpm -qa *.rpm`

  b. `rpm install *.rpm`

  c. `rpm -q *.rpm`

  d. `rpm -i *.rpm` (CORRECT)

18) After building software from source and running the ```./configure``` command, what is the next step?

  a. Run the ```make install``` command

  b. Run the ```sudo make install``` command

  c. Run the ```install``` command

  d. Run the ```make``` command (CORRECT)

19) What is the name of the new package managers developed by Canonical and Red Hat?

  a.  flatpak and apt

  b.  flatpak and snap (CORRECT)

  c.  snapcraft and flatter

  d.  dnf and apt

20) What is the DNF command used to install additional software repositories? Use this URL to an RPM: http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm

  a. `sudo dnf install repo http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm`

  b. `sudo dnf http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm`

  c. `sudo dnf install http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm`

  d. `sudo install http://download1.rpmfusion.org/free/el/updates/7/x86_64/r/rpmfusion-free-release-7-4.noarch.rpm` (CORRECT)
  