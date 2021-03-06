# Chapter 03 Labs

You will need to do some research and find the download links for the Linux and BSD based distros below and install them in VirtualBox. You will need to install the latest version of [VirtualBox 6.1.x](https://virtualbox.org "VirtualBox Download site") in order to complete this exercise; it can be installed via Chocolatey or Brew package managers as well.  If you are using an M1 Mac, you will need to purchase a copy of a comparable software called [Parallels Virtualization for M1 Macs](https://www.parallels.com/ "Parallels virtualization for M1 Mac") Complete each install to disk.  Assume each instance listed below is 64-bit version. Take a screen shot of each desktop after logging in.  There are 17 different distributions listed.  If a version is not listed, assume the latest version unless noted.

* Debian Based
  * Ubuntu 20.04 Desktop edition

![](../images/Lab-3/Ubuntu2004.png)

  * Lubuntu 20.04 Desktop edition

![](../images/Lab-3/Lubuntu-20.04.png)

  * XUbuntu 20.04 Desktop edition

![](../images/Lab-3/XUbuntu-20.04.png)

  * Ubuntu 20.04 Server edition



  * Trisquel Linux

![](../images/Lab-3/Trisquel-Linux.png)

  * Solus Linux - MATE

![](../images/Lab-3/Solus-Linux-MATE.png)


  * PureOS

![](../images/Lab-3/PuresOS.png)


* Red Hat Based
  * Fedora 34 - Workstation edition

![](../images/Lab-3/Fedora-34.png)

  * CentOS 8 Stream - Minimal install

![](../images/Lab-3/CentOS.png)

* Illumos Based
  * OmniOS Community Edition

  ![](../images/Lab-3/OmniOS.png)

* BSD based
  * FreeBSD

  ![](../images/Lab-3/freebsd.png)


* Linux
  * Alpine Linux - Standard

  ![](../images/Lab-3/AlpineLinux.png)

  * MX Linux

  ![](../images/Lab-3/MXLinux.png)


  * PCLinuxOS - Xfce mini

  ![](../images/Lab-3/PCLinux.png)

  * Linux Mint

    ![](../images/Lab-3/LinuxMint.png)


* Network Based Install
  * openSUSE Leap

    ![](../images/Lab-3/opensuse.png)

  * Debian 11.x

      ![](../images/Lab-3/Debian.png)


![*Sample Deliverable*](images/Chapter-03/lab-example/virtualbox-ubuntu.png "Sample Deliverable")

## Python pyttsx3

Install these pre-requisites needed for the speech-to-text library. You will also need to install Python3 dependencies to use pip

```bash
sudo apt-get install python3-dev python3-setuptools python3-pip libespeak1 libespeak1-dev
```

Then use Python3 pip installer to install the Python3 Speech-to-Text library:

```bash
python3 -m pip install pyttsx3
```

To test this create a file named `py-speech.py` using a Text Editor, Visual Studio Code, or a similar application with this content:

```python
import pyttsx3
engine = pyttsx3.init()
engine.say("I will speak this text")
engine.runAndWait()
```

Upon saving this file, from the commandline, execute this code with the command: `python3 py-speech.py` and if you hear the computer voice you will have successfully installed the modules via Python3.
