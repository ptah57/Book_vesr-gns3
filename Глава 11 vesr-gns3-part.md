����� 11. ��������� ������������ �������� ����� ���������.

���� ������:
��������� ����������� ��������� ��������������� vesr � ����������� ����� � ���� �������� �� ������ � ������������� ��������� �� ��������� DMVPN.
��� ���������� ������������ ����������� ��������� ������������� � �������� ���������� �������� ������������� ��� ��������. � ���������� ������ ���� ����������� ���������� �������� ����� ����� �������� ����� �������� � ����������� ������ �� ���������� gre-over-ipsec � ������������ �������������� ip ������� ���������� ��������� ospf. ��� ����� ����������� ������ ����� �� �������������� ������� ����� ��������� �� �����. ������� ����������� ���� �������� ���� ��� �������� �������� ���� ����� ���� �� �����:
 

��� ��������� ��������� ������ ����� ����� ����� ������� �������� ��������� �� ������ �� ��������������� � ����, ��� ��������� ����� ��������� � �������.
������ ��� ������ �������� DMVPN.	
��� ����� �������� DMVPN:
��������� ������� �������� �� ���� ������ ��� ��������� �����������-DMVPN (Dynamic Multipoint Virtual Private Network)�� ����������, ������������� ��������� Cisco ��� ��������� � ��������������� ���������� ����� VPN.���� ����� ��� ����������� ���������� � ����������� ���������� ����������� ������� ����� (VPN) ������ ������������ �����, ����� ��� �������� ��� ������� WAN-���� 
���������� DMVPN:
����� ��������� �������� � �������� ������� ����������� ������ ��� ����� �����.
������ � ������� ������ ���������. ��������, ��� ������� ���������� � ���� ��������, ����� ��� �� � �����, ��� ��� �������������� ��������� ��� �������� ������� � ������� ���� ��� ��������� ���� ��������������.
��������� ���������� ������������ ������, ���� �������� ���������� �����������������. 
������� ������
� ������������ ������������ DMVPN ������������ ����������Hub-and-Spoke: ���� ����������� ���� (Hub) �������� � ����������� ��������� ������ (Spoke). ��� ���� Spoke ����� ������������� ������� ����� ���� Hub.������������ DMVPN�� ����������� ������������� ������������ ������ ���������� (��������) ����� ������ Spoke, ����� ���� Hub. ��� ��������� �������� � ��������� �������� �� ����������� ����.� 
��������� ���������� DMVPN:
NHRP (Next Hop Resolution Protocol)�� �������� ��� ������������� ����������� ���������� ����� (next hop) � ����. ��������� ����� �������� �������� IP-������ ������ ����� � ����, ��� ��������� ������������� ������ ������� ����� ����.
mGRE (Multipoint GRE)�� ������������ ��� �������� ������������� �������� GRE, ��� ��������� ������ ������� ����������� ��������� �������� �����.
IPsec�� ������������ ���������� � ������ ������, ������������ ����� ������� DMVPN.
Dynamic Routing Protocols�� DMVPN ������������ ������������ ���������������� ���������, ����� ��� OSPF, EIGRP, BGP, ��� ��������� ���������������� ������������� � ���� VPN � ������������ � ����������������.
��������� ������� � �� ��������:
NBMA���nonbroadcast, multiaccess network, �� ���� ���� � ������������� �������� ��� �������������. � ����� ����� ���������, ��������, ISDN, ATM, X25, Frame Relay (���� ���������������� � ������������� ������).�bzoel.iod12vzecr6ihe4p.cloudfront.net
NBMA IP�� ������������������ IP-����� �� ���������� (underlay IP).�bzoel.io
Tunnel IP�� �� �������� ������� ��� ���������, � ���������� ����� ������ ������� (overlay IP).�bzoel.io
NHRP���Next Hop Resolution Protocol, �������� ���������� ���������� ����, ������� ��������� ����������� ������������� ����������. ���������� ������������� � ����� NBMA, ����� ��� Frame-Relay � Asynchronous Transfer Mode (ATM).�habr.comd12vzecr6ihe4p.cloudfront.net
������������ ���������� DMVPN
������� ����� ������ ������ � L3VPN-���� ��������� �����������. ������������� �������  ����� ���������������� �������  (Spoke) � ������������ ����� (Hub). ����� ����� �������������� ��������  ����� ��������� ������� ����� ����� �� ���� �������������. ��� ���� � ��������������� ��������  ����� ���� ������������ ������� ������, ��� �� ����� �� ������� ��������������� ����. �������� � ������ � ���������� ������������ �������������. ���������� ��� ���������� ����� ����� ����������� ����� ������ ��. ����� ����������� ��������NHRP�� NBMA Next Hop resolution Protocol. �� ��������� ����������� ������� ������ �������� �����, ������� ������ ������������ � ��������. �� ��� � �������� ����������� ���������� multipoint VPN. ��� (����������� ����) ����� ��������� ��� ������ (NHS � Next-Hop Server), � ��� �������� ���� ����� ��������� (NHC � Next-Hop Client).
���������� ���������� DMVPN
� ������ ������� ��� ��, ��� �������� �������������, ���������� ��������� CISCO � ��� ��������� ��� �� ������ ��������������. � ��������� ���������� ����������� , ��� 
� ������� ����� ������� ��������� ����������� �� ����������� � �������� ����������� ������� �������� ��� �������� � ��� �� ����� ������������ ��� ����� �������. ����� �������� ������� ����� ��������� ���������, �.�. � 99% ����� ������������ ��� ������� � ������������ ����� ��������, � ������� ��������� ����-�����.
�������:
��������� ���������� ����������� �� IP ������� ���������������, ����������� � ����� ����� ������������ �������� ( ��. ����� 8. ��������� GRE-over-IPSEC � �������������� vESR.)
����������� IPsec-������� � Policy-based IPsec VPN ��� ������ ��������� � ������������� GRE-���������. ( ��. ����� 8. ��������� GRE-over-IPSEC � �������������� vESR.)
������� GRE-������� � ������� � ����� ��� ����������������.
��������� GRE-������� � ����� multipoint.
���������� ��������� IP-����� ��� ��������� �������.
������ IP-����� �� �������. � �������� ������������ ����� ��������� DHCP-������ ��� ��������� IP-������ �� DHCP-�������.
������ ������������ ������������ ����������� ������ � �������� NBMA-�������.
������ ����������� (����������)� ����� NHRP-�������.
���������� �������� �������������� �������. dynamic ���  nhs 
�������� ������ ��������� NHRP.
������������ IP-��������� ����������� ��������� ������������ ������������� eBGP.
��� ����� BGP
BGP (Border Gateway Protocol)�� ��� �������� �������� ������������� ����������. ������������� ������ ������� ������ ����������� ����� ���������� ����������� ����� ������������� ���������� ����������. BGP ���������� ������ � �������� ���������� ������� (AS � Autonomous System), ������� ��� ����������� � ���������� ������.
��� ����� AS
 ���������� �������(autonomous system, AS) � �������IP-����� � ���������������, ����������� ����� ��� ����������� �����������, �������� ������ �������� ������������� � ���������� (RFC 1930).
�� ����, �������� � �� ��� ����, ��� ����������������������� ������, ������� ������� ���� � ������. ������AS���������������������� ����������� �����(Interior Gateway Protocol,�IGP), ��������OSPF����EIGRP. � ��� ������������� ����� ����������AS������������������������������ �����(Exterior Gateway Protocol,�EGP). ������������EGP, ������� ������������ � ��������� ����� � ���BGP�(Border Gateway Protocol).
�������IP-�������, ������AS������� ���� ����������� � ���������. �������� �������� ����� �������� ��, ���BGP����������� �����AS���� ������ ��������� �������������� ��������� ������ � �������������. �����BGP������� � ��������, ������� ����� ��� ����������� �����AS�� ����� ����, �� ����� ��������. �� ����� ������������ ������ AS ������� � 65000 �� �������� ������� AS ��� ����������� �������������.

��������� ��� ��������� ������ ������� IKE:
������ �����-��������: 2;
�������� ����������: AES128;
�������� ��������������: SHA1.

��������� ��� ��������� IPsec:
�������� ����������: AES128;
�������� ��������������: SHA1.

��������� ��������� ���������� ���������� ���������� GRE-������� (��. ��������������� GRE-��������).
���� � 1 �� 3 ���������� ��� , ��� ���� ������� � ���������� ������. ����� �� ��������, ��������� ��������������� � ��������� �������� gre multipath :
��������� gre multipath
��������� ������������ ��� ������� ����� �� ���������� ����, �� ������������� ������ ������������ ��������������� ��������.
��������� ������� �� Hub (��� ������������� � ������ vesr124-2-1):
vesr124-2-1 login: admin
Password:
********************************************
*             Welcome to vESR              *
********************************************
vesr124-2-1# sh run tunnels gre 10
tunnel gre 10
  ttl 18
  security-zone UNTRUST
  local address 10.10.10.2
  remote address 10.10.20.2
  ip address 192.168.100.1/24
  ip ospf instance 1
  ip ospf
  enable
exit
vesr124-2-1#

�������� ������ ������:
vesr124-2-1# config
vesr124-2-1(config)# tunnel gre 10
vesr124-2-1(config-gre)# mtu 1416
vesr124-2-1(config-gre)#
��������� ����� � ���������� ������� �������� � ������ ������� � ��������� ������� � ������������� �����:
vesr124-2-1(config-gre)# no remote address
vesr124-2-1(config-gre)# multipoint

��� ������ ��������� BGP ���������� ��������� ����������� ������� �� ����� 179 � ���� UNTRUST, � ������� �������� �������. ��� ����� �������� ������-������:
 
vesr124-2-1# configure
vesr124-2-1(config)# object-group service to_bgp
vesr124-2-1(config-object-group-service)#   port-range 179
vesr124-2-1(config-object-group-service)# exit
vesr124-2-1(config)#

����� ����� ������� ��� �������� TCP ������� �� ����� ����� ����� ���� �������:

vesr124-2-1(config)# security zone-pair UNTRUST self
vesr124-2-1(config-security-zone-pair)#   rule 11
vesr124-2-1(config-security-zone-pair-rule)#     action permit
vesr124-2-1(config-security-zone-pair-rule)#     match protocol tcp
vesr124-2-1(config-security-zone-pair-rule)#     match destination-port object-g
roup to_bgp
vesr124-2-1(config-security-zone-pair-rule)#     enable
vesr124-2-1(config-security-zone-pair-rule)#   exit
vesr124-2-1(config-security-zone-pair)# exit
vesr124-2-1(config)#

������� � ��������� NHRP. �������� �������� �������������� ( �������� ������� ����� � ������ )  �������� � ����������� ���������� ������:

vesr124-2-1(config)# tunnel gre 10
vesr124-2-1(config-gre)# ip nhrp multicast dynamic

��������� ������������� BGP
��������� ��� ������ ������������ �������� ���������� �������� ���������, �� ������  ��������� ��������� ������������ ������������� eBGP ��� Hub. ���������� , �������� ������������, ��� eBGP ����������� ���� ������� ����� ���������� ����� � ��������� ������������� ��������. ���������� ����� route map, ������� ������� � ��� ������� ������� ������ ����� �������������� ���� 172.16.1.0/24, 
172.16.2.0/24, 172.16.3.0/24.


vesr124-2-1#  config
 ���������� ����������vesr124-2-1(config)# route-map PERMIT_ALL
vesr124-2-1(config-route-map)#   rule 1
vesr124-2-1(config-route-map-rule)# match ip address 172.16.1.0/24
vesr124-2-1(config-route-map-rule)# exit
vesr124-2-1(config-route-map)# exit
vesr124-2-1(config-route-map)#   rule 2
vesr124-2-1(config-route-map-rule)# match ip address 172.16.2.0/24
vesr124-2-1(config-route-map-rule)# exit
vesr124-2-1(config-route-map)# exit
vesr124-2-1(config-route-map)#   rule 3
vesr124-2-1(config-route-map-rule)# match ip address 172.16.3.0/24
vesr124-2-1(config-route-map-rule)# exit
vesr124-2-1(config-route-map)# exit
vesr124-2-1(config)# exit

����� ������������� ��� ������ BGP. ��������� ������� � ������� ������ ������� ������� � ������� �������, ��������� ����� ������ �� ������ ����� PERMIT_ALL, ������������ ������������ �������������� � ����������� ��������� ����:
vesr124-2-1(config)# router bgp 65005

�������� ����� BGP c ������� ���������� ������� ���� 65005.

vesr124-2-1(config-bgp)#   neighbor 10.10.20.2

�������� ������ � ������� ����� ������� �������

vesr124-2-1(config-bgp-neighbor)#     remote-as 65008

����� ���������� ���� ������� ������� 65008

vesr124-2-1(config-bgp-neighbor)#     address-family ipv4 unicast

��������� ����� ����������� � ���.

vesr124-2-1(config-bgp-neighbor-af)#       route-map PERMIT_ALL out

������� ����� ������� ��� ������������ ����� ������.

vesr124-2-1(config-bgp-neighbor-af)#       enable
vesr124-2-1(config-bgp-neighbor-af)#     exit
vesr124-2-1(config-bgp-neighbor)# exit

��� �� ��� ������� �������. � ���� ����� ���������� ������� ����� 65004

vesr124-2-1(config-bgp)# neighbor 10.10.30.2
vesr124-2-1(config-bgp-neighbor)# remote-as 65004
vesr124-2-1(config-bgp-neighbor)# address-family ipv4 unicast
vesr124-2-1(config-bgp-neighbor-af)# route-map PERMIT_ALL out
vesr124-2-1(config-bgp-neighbor-af)# enable
vesr124-2-1(config-bgp-neighbor-af)# exit
vesr124-2-1(config-bgp-neighbor)# )# enable
vesr124-2-1(config-bgp)#   address-family ipv4 unicast
vesr124-2-1(config-bgp-af)#     redistribute connected
vesr124-2-1(config-bgp-af)#   exit
vesr124-2-1(config-bgp)#   enable
vesr124-2-1(config-bgp)# exit
vesr124-2-1(config)# exit

��������� �� HUB IPSEC:
�������� ������� ��� ������ �������, ������������� �� ���������� � ������ DH
vesr124-2-1# config
vesr124-2-1(config)#
vesr124-2-1(config)# security ike proposal ike_prop1
vesr124-2-1(config-ike-proposal)#   authentication algorithm md5
vesr124-2-1(config-ike-proposal)#   encryption algorithm aes128
vesr124-2-1(config-ike-proposal)#   dh-group 2
vesr124-2-1(config-ike-proposal)# exit
vesr124-2-1(config)#

�������� �������� ������ �������
vesr124-2-1(config)#  security ike policy ike_pol1
vesr124-2-1(config-ike-policy)#   pre-shared-key ascii-text P@ssw0rd
vesr124-2-1(config-ike-policy)#   proposal ike_prop1
vesr124-2-1(config-ike-policy)# exit

�������� ����� ��� ������ �������  � ������������� ��� ����-��������� ����� � ���� ����������: 
vesr124-2-1(config)#  security ike gateway ike_gw1
vesr124-2-1(config-ike-gw)#   ike-policy ike_pol1
vesr124-2-1(config-ike-gw)#   local address 10.10.10.2
vesr124-2-1(config-ike-gw)#   local network 10.10.10.2/32 protocol gre
vesr124-2-1(config-ike-gw)#   remote address any
vesr124-2-1(config-ike-gw)#   remote network any 
vesr124-2-1(config-ike-gw)#   mode policy-based
vesr124-2-1(config-ike-gw)# exit
vesr124-2-1(config)#exit
vesr124-2-1#commit
vesr124-2-1#confirm

�������� IPSEC VPN ������ ���� �����:

security ipsec vpn ipsec1
type transport ike
establish-tunnel route
ike gateway ike_gw1
ike ipsec-policy ipsec_pol1
enable
exit

�������� � ���������� BGP, ������� ������� �������� (��������� � ���������� ������ )  � ��������� OSPF �� �������� ������� 10

vesr124-2-1(config)# tunnel gre 10
vesr124-2-1(config-gre)# no   ip ospf
vesr124-2-1(config-gre)# no ip ospf instance
vesr124-2-1(config-gre)# exit
vesr124-2-1(config)# exit
vesr124-2-1#

������� gre 10 ������ ��������� ���:
vesr124-2-1# sh running-config tunnels gre 10
tunnel gre 10
  ttl 18
  mtu 1416
  multipoint
  security-zone UNTRUST
  local interface gigabitethernet 1/0/1
  ip address 192.168.100.1/24
  ip nhrp multicast dynamic
  enable
exit

����������� � ������� IPSEC � �������� DMVPN.
vesr124-2-1# config
vesr124-2-1(config)# tunnel gre 10
vesr124-2-1(config-gre)# ip nhrp ipsec ipsec1 dynamic
vesr124-2-1(config-gre)# ip nhrp enable
vesr124-2-1(config-gre)# enable
vesr124-2-1(config-gre)# exit
vesr124-2-1(config)# exit

��������� ��������� �� �������������� �� ��������. ��������� ��������� � ������� �� �������������� vesr124-2-1 � ��������� � �������������� ������� ������� vesr124-2-2.
������ ��������� � ��������� ������� tunnel gre 10:

����������� - ����� � ������� PDF �������� �� Boosty-[![������ ������](https://img.shields.io/badge/���������_�����_�-Boosty-6c5ce7)](https://boosty.to/rinatxf/posts/5f4f7eb0-97ca-4a32-8970-30e22abfd186?share=success_publish_link) 
