# Directadmin-1.595-Nulled
Directadmin 1.595 Nulled

Directadmin-1.595-Nulled For Centos 7 64bit

[root@sucuri ~]# yum -y install nano wget perl

[root@sucuri ~]# wget https://raw.githubusercontent.com/LinuxGuard/Directadmin-1.59-Nulled/master/setup.sh

[root@sucuri ~]# chmod +x setup.sh

[root@sucuri ~]# ./setup.sh

[root@sucuri ~]# firewall-cmd --zone=public --add-port=2222/tcp --permanent

[root@sucuri ~]# firewall-cmd --zone=public --add-port=21/tcp --permanent

[root@sucuri ~]# firewall-cmd --zone=public --add-port=80/tcp --permanent

[root@sucuri ~]# firewall-cmd --zone=public --add-port=25/tcp --permanent

[root@sucuri ~]# firewall-cmd --reload

[root@sucuri ~]# systemctl restart directadmin

[root@sucuri ~]# cd /usr/local/directadmin/conf/

[root@sucuri ~]# systemctl stop directadmin

[root@sucuri ~]# rm -rf /usr/local/directadmin/conf/license.key

[root@sucuri ~]# wget -O /usr/local/directadmin/conf/license.key https://www.plesk.com.vn/license.key

[root@sucuri ~]# chmod 600 /usr/local/directadmin/conf/license.key

[root@sucuri ~]# chown diradmin:diradmin /usr/local/directadmin/conf/license.key

[root@sucuri ~]# ifconfig eth0:100 103.237.147.148 netmask 255.0.0.0 up

[root@sucuri ~]# echo 'DEVICE=eth0:100' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

[root@sucuri ~]# echo 'IPADDR=103.237.147.148' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

[root@sucuri ~]# echo 'NETMASK=255.0.0.0' >> /etc/sysconfig/network-scripts/ifcfg-eth0:100

[root@sucuri ~]# systemctl restart network

[root@sucuri ~]# /usr/bin/perl -pi -e 's/^ethernet_dev=.*/ethernet_dev=eth0:100/' /usr/local/directadmin/conf/directadmin.conf

[root@sucuri ~]# systemctl start directadmin

Done:)
