# Review Questions - Chapter 12

1) Using the ip2 suite of tools, which command(s) would show your IP address?

   a. `ifconfig`

   b. `ipconfig`

   c. `ip address show` (CORRECT)

   d. `ip a sh`

2) Using the ip2 suite of tools, which command would show your routing table?

   a. `ss`

   b. `route`

   c. `ip route show` (CORRECT)

   d. `ip -r`

3) What tool could you use to establish if a server is responding to requests?

   a. `pong`

   b. `ping` (CORRECT)

   c. `google`

   d. `traceroute`

4) What is the purpose of a netmask?

A Netmask is a 32-bit mask used to divide an IP address into subnets and specify the network's available hosts.Netmask is used to define the class of network and range of IP address.It also defines how many IP addresses are available to use.

5) What is the purpose of DNS?

DNS is used as a directory to translate domain names to IP address.As it is easy to remember domain names than IP address of a website.DNS contains IP address of websites mapped to domain names.It performs dns lookup of our domain name and provides ip address to the browser.
6) What is the name of the systemd firewall?

   a. systemd-firewalld

   b. systemd-firewall

   c. firewalld-cmd (CORRECT)

   d. ufw

7) What would be the command to list all of the firewalld public zone ports in use?

   a. `sudo systemctl status firewalld` (CORRECRT)

   b. `sudo firewalld-cmd --zone=public --list-all`

   c. `sudo firewall-cmd --zone=public --list-all`

   d. `sudo firewall-cmd --list-all`

8) If you had a CIDR block of /24 and a network address of 192.168.1.0, how many IP addresses would you have?

   a. 10

   b. 0

   c. 24

   d. 256 (CORRECT)

9) What is the default port for HTTPS (TLS/SSL)?

   a. 80
   b. 3000
   c. 8080
   d. 443 (CORRECT)

10) Using Network Manager, what tool is used to release a DHCP address from the command line?

    a. `rhclient`

    b. `ipconfig /release` (CORRECT)

    c. `dhclient -r`

    d. `xclient -r`

11) Using the ip2 suite, what command can be used to monitor and examine all current local ports and TCP/IP connections?

    a.  `ss`

    b.  `net`

    c.  `wireshark`

    d.  `netstat` (CORRECT)

12) Where are your network card settings located on Ubuntu while using Network Manager?

/etc/network/interfaces

13) Where are your network card settings located on Fedora using Network Manager?

/etc/sysconfig/network-scripts

14) Where are your network card settings located on Ubuntu using Netplan?

/etc/netplan/config.yaml

15) What are the two major opensource webservers?

    a. Apache, Nginx (C0RRECT)

    b. openhttpd, Nginx

    c. Apache, IIS

    d. Apache, Tomcat

16) What are two related and major opensource relational databases?

    a. SQL and MySQL

    b. MariaDB and MySQL (C0RRECT)

    c. MySQL and Oracle DB

    d. Nginx and MySQL

17) What command would you type to get to the MySQL command line prompt as the root user?

 mysql -u root -p

18) What is the file location that the system uses as a *local DNS* for resolving IP?

    a. `etc/systemd/hostd`

    b. `/etc/hosts` (CORRECT)

    c. `/etc/allow`

    d. `/etc/etc/etc`

19) What flag would you add to this command to make it survive a reboot: `sudo firewall-cmd --zone=public --add-port=22/tcp`

    a. `--peppermint`

    b. `--permenant` (CORRECT)

    c. `--allow`

    d. `--list-all`

20) Before systemd, NIC interface naming schemes depended on a driver based enumeration process. They switched to a predictable network interface naming process that depends on what for the interface names?

    a. driver loading order (CORRECT)

    b. interface names depend on physical location of hardware (bus enumeration) (CORRECT)

    c. kernel version

    d. What ever Lennart Poettering feels like naming them
