Virtual Routers
-------------------------
- Packet tracer (Simulator)
- GNS3
- Vyos
- vyatta


*Cisco Router Modes


User Mode
router>enable | en

Previledge Mode
router#configure terminal | conf t

Global COnfiguration Mode
router(config)#interface fastethernet 0/0
router(config)#ip address 192.168.1.1 255.255.255.0
router(config)#no shutdown


Default vyos credentials
----------------------------------------------------------

Username : vyos
password : vyos

Default vyatta credentials
----------------------------------------------------------

Username : vyatta
password : vyatta


TO CONFIGURE IP
----------------------------------------------------------
# DYNAMIC IP #

# configure
# set interfaces ethernet eth0 address dhcp
# commit
# save
# exit

# STATIC IP #

# configure
# set interfaces ethernet eth0 address 192.168.1.5/24
# commit
# save
# exit


*ENABLING SERVICES

SSH - Secure Shell
# configure
# set service ssh
# commit
# save

HTTPS
# configure
# set service https
# commit
# save

TELNET
# configure
# set service telnet
# commit
# save



enable this also
------------------------
# configure

# set service snmp community public authorization ro

# set service snmp community private authorization rw

# commit

# save

# exit



