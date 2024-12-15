# Cisco_ERDD

...

2.1.1 EDGARAS

2.1.2 Disabling unused ports

2.1.3 Security Updates: Separation of unused ports to separate vlan 99 and disabling them

2.1.4 Protect critical network devices with a password for enable mode and access to configuration

################

line console 0

password a

login

logging synchronous

exec-timeout 3 0

exit

enable password a

exit

#################

2.1.5
