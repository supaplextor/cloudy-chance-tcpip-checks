# cloudy-chance-tcpip-checks

Beware, there is so much scope creep possible with this toolset.

I had a prior issue with TCP-MSS that only affected one site (but not the CDN, not other sites). This kit will diagnose related issues from the local, or other perspectives.

Next steps: 1. Obtain packet captures at egress now (easy enough). 2. Obtain packet captures from egress during issue.

Step 2 will involve one or more of the following: a. Gigabit connectivity. b. Linux using two interfaces in a bridge. c. SRX-240 (Juniper Networks) with two interfaces in an isolated vlan + sniffing. d. ASUS TM-AC1900 802.11 ac/n/g/b/a (issue is probably in a presumable Linux-OEM-WRT kernel; nic settings; iptables; etc)
