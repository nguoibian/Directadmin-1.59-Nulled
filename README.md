# Directadmin-1.595-Nulled
Directadmin 1.595 Nulled

Directadmin-1.595-Nulled For Centos 7 64bit

# yum -y install nano wget perl

# wget https://raw.githubusercontent.com/lehieuit/Directadmin-1.53-nulled/master/setup.sh

# chmod +x setup.sh

# ./setup.sh

# firewall-cmd --zone=public --add-port=2222/tcp --permanent

# firewall-cmd --zone=public --add-port=21/tcp --permanent

# firewall-cmd --zone=public --add-port=80/tcp --permanent

# firewall-cmd --zone=public --add-port=25/tcp --permanent

# firewall-cmd --reload

# systemctl restart directadmin

# cd /usr/local/directadmin/conf/

# systemctl stop directadmin

# rm -rf /usr/local/directadmin/conf/license.key

# wget -O /usr/local/directadmin/conf/license.key https://www.plesk.com.vn/license.key

# chmod 600 /usr/local/directadmin/conf/license.key

# chown diradmin:diradmin /usr/local/directadmin/conf/license.key

# ifconfig eth0:100 103.237.147.148 netmask 255.0.0.0 up

# echo 'DEVICE=eth0:100' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

# echo 'IPADDR=103.237.147.148' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

# echo 'NETMASK=255.0.0.0' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

# systemctl restart network

# /usr/bin/perl -pi -e 's/^ethernet_dev=.*/ethernet_dev=eth0:100/' /usr/local/directadmin/conf/directadmin.conf

# systemctl start directadmin

Done:)