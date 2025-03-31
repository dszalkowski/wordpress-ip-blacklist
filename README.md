I've created IPv4 and IPv6 blacklists from hosts which send useless requests to our web sites.

I've collected this CIDR IP addresses from my Apache logs during several months an I've added them in my Iptables configuration files on my Linux Fedora Server :
- /etc/sysconfig/iptables
- /etc/sysconfig/ip6tables
