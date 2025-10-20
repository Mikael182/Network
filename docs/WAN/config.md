System Bootstrap, Version 12.1(3r)T2, RELEASE SOFTWARE (fc1)
Copyright (c) 2000 by cisco Systems, Inc.
PT 1001 (PTSC2005) processor (revision 0x200) with 60416K/5120K bytes of memory

Readonly ROMMON initialized

Self decompressing the image :
######################### [OK]

              Restricted Rights Legend

Use, duplication, or disclosure by the Government is
subject to restrictions as set forth in subparagraph
(c) of the Commercial Computer Software - Restricted
Rights clause at FAR sec. 52.227-19 and subparagraph
(c) (1) (ii) of the Rights in Technical Data and Computer
Software clause at DFARS sec. 252.227-7013.

           cisco Systems, Inc.
           170 West Tasman Drive
           San Jose, California 95134-1706



Cisco Internetwork Operating System Software
IOS (tm) PT1000 Software (PT1000-I-M), Version 12.2(28), RELEASE SOFTWARE (fc5)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2005 by cisco Systems, Inc.
Compiled Wed 27-Apr-04 19:01 by miwang

PT 1001 (PTSC2005) processor (revision 0x200) with 60416K/5120K bytes of memory
.
Processor board ID PT0123 (0123)
PT2005 processor: part number 0, mask 01
Bridging software.
X.25 software, Version 3.0.0.
1 Gigabit Ethernet/IEEE 802.3 interface(s)
2 Low-speed serial(sync/async) network interface(s)
32K bytes of non-volatile configuration memory.
63488K bytes of ATA CompactFlash (Read/Write)

Press RETURN to get started!



Router>enable
Router#con
Router#config 
Router#config terminal 
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#host
% Incomplete command.
Router(config)#host
Router(config)#hostname R1_Malolepszy
R1_Malolepszy(config)#
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface gi
R1_Malolepszy(config)#interface gigabitEthernet 7/0
R1_Malolepszy(config-if)#ip ad
R1_Malolepszy(config-if)#ip address 189.98.75.1 255.255.255.0
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

R1_Malolepszy(config-if)#
%LINK-5-CHANGED: Interface GigabitEthernet7/0, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet7/0, changed state to up
exit
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface ser
R1_Malolepszy(config)#interface serial 8/0
R1_Malolepszy(config-if)#ip add
R1_Malolepszy(config-if)#ip address 10.10.40.1 255.255.255.252
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

%LINK-5-CHANGED: Interface Serial8/0, changed state to down
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 
R1_Malolepszy(config-if)#exit
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface serial 9/0
R1_Malolepszy(config-if)#ip address 10.10.10.1 255.255.255.252
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

%LINK-5-CHANGED: Interface Serial9/0, changed state to down
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 
R1_Malolepszy(config-if)#exit
R1_Malolepszy(config)# do wr


System Bootstrap, Version 12.1(3r)T2, RELEASE SOFTWARE (fc1)
Copyright (c) 2000 by cisco Systems, Inc.
PT 1001 (PTSC2005) processor (revision 0x200) with 60416K/5120K bytes of memory

Readonly ROMMON initialized

Self decompressing the image :
######################### [OK]

              Restricted Rights Legend

Use, duplication, or disclosure by the Government is
subject to restrictions as set forth in subparagraph
(c) of the Commercial Computer Software - Restricted
Rights clause at FAR sec. 52.227-19 and subparagraph
(c) (1) (ii) of the Rights in Technical Data and Computer
Software clause at DFARS sec. 252.227-7013.

           cisco Systems, Inc.
           170 West Tasman Drive
           San Jose, California 95134-1706



Cisco Internetwork Operating System Software
IOS (tm) PT1000 Software (PT1000-I-M), Version 12.2(28), RELEASE SOFTWARE (fc5)
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2005 by cisco Systems, Inc.
Compiled Wed 27-Apr-04 19:01 by miwang

PT 1001 (PTSC2005) processor (revision 0x200) with 60416K/5120K bytes of memory
.
Processor board ID PT0123 (0123)
PT2005 processor: part number 0, mask 01
Bridging software.
X.25 software, Version 3.0.0.
1 Gigabit Ethernet/IEEE 802.3 interface(s)
2 Low-speed serial(sync/async) network interface(s)
32K bytes of non-volatile configuration memory.
63488K bytes of ATA CompactFlash (Read/Write)

Press RETURN to get started!



Router>enable
Router#con
Router#config 
Router#config terminal 
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#host
% Incomplete command.
Router(config)#host
Router(config)#hostname R1_Malolepszy
R1_Malolepszy(config)#
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface gi
R1_Malolepszy(config)#interface gigabitEthernet 7/0
R1_Malolepszy(config-if)#ip ad
R1_Malolepszy(config-if)#ip address 189.98.75.1 255.255.255.0
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

R1_Malolepszy(config-if)#
%LINK-5-CHANGED: Interface GigabitEthernet7/0, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet7/0, changed state to up
exit
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface ser
R1_Malolepszy(config)#interface serial 8/0
R1_Malolepszy(config-if)#ip add
R1_Malolepszy(config-if)#ip address 10.10.40.1 255.255.255.252
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

%LINK-5-CHANGED: Interface Serial8/0, changed state to down
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 
R1_Malolepszy(config-if)#exit
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface serial 9/0
R1_Malolepszy(config-if)#ip address 10.10.10.1 255.255.255.252
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 

%LINK-5-CHANGED: Interface Serial9/0, changed state to down
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown 
R1_Malolepszy(config-if)#exit
R1_Malolepszy(config)#
Router(config)#interface gigabitEthernet 7/0
Router(config-if)#ip address 192.168.3.1 255.255.255.250
Bad mask 0xFFFFFFFA for address 192.168.3.1
Router(config-if)#ip address 192.168.3.1 255.255.255.0
Router(config-if)#no sh

Router(config-if)#
%LINK-5-CHANGED: Interface GigabitEthernet7/0, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet7/0, changed state to up
no sh
Router(config-if)#no shutdown 
Router(config-if)#ip dh
Router(config-if)#ip dhcp Pool
Router(config-if)#ip dhcp Pool WSB_DHCP_SERVER
Router(dhcp-config)#def
Router(dhcp-config)#default-router 192.168.3.1
Router(dhcp-config)#dns
% Incomplete command.
Router(dhcp-config)#network 192.168.3. 255.255.255.0
                            ^
% Invalid input detected at '^' marker.
    
Router(dhcp-config)#network 192.168.3.0 255.255.255.0
Router(dhcp-config)#ex
Router(dhcp-config)#exit 
Router(config)#ip dhc
Router(config)#ip dhcp exc
Router(config)#ip dhcp excluded-address 192.168.3.2
Router(config)#ip dhcp excluded-address 192.168.3.3
Router(config)#ip dhcp excluded-address 192.168.3.4
Router(config)#do wr
Building configuration...
[OK]
Router(config)#
Router#config 
Router#config terminal 
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#host
% Incomplete command.
Router(config)#host
Router(config)#hostname R1_Malolepszy
R1_Malolepszy(config)#
R1_Malolepszy(config)#inter
R1_Malolepszy(config)#interface gi
R1_Malolepszy(config)#interface gigabitEthernet 7/0
R1_Malolepszy(config-if)#ip ad
R1_Malolepszy(config-if)#ip address 189.98.75.1 255.255.255.0
R1_Malolepszy(config-if)#no sh
R1_Malolepszy(config-if)#no shutdown
R1_Malolepszy(config)#ro 
R1_Malolepszy(config)#ro
R1_Malolepszy(config)#router rip
R1_Malolepszy(config-router)#189.98.75.0
                             ^
% Invalid input detected at '^' marker.
    
R1_Malolepszy(config-router)#net
R1_Malolepszy(config-router)#network 189.98.75.0
R1_Malolepszy(config-router)#network 10.10.40.0
R1_Malolepszy(config-router)#network 10.10.10.0
R1_Malolepszy(config-router)#do wr
R1_Malolepszy(config-router)#do wr
Building configuration...
