# vm_pt2
==================

File 1

1. bring up the machines, navigate to the directory containing the Vagrantfile and run: 
vagrant up
2. SSH into machine1
vagrant ssh machine1
3.	Check IP address
ip addr show               -> should be 192.168.56.101
exit
4. SSH into machine2
vagrant ssh machine2
6.	Check IP address
ip addr show               -> IP is dynamic, could be any, e.g. 192.168.56.107
7. Ping machine1 from machine2
ping 192.168.56.101        -> pingable
exit
8. SSH into machine1
vagrant ssh machine1
9.	Ping machine2 from machine1
ping 192.168.56.107        -> pingable
exit
vagrant destroy
=================

File 2

