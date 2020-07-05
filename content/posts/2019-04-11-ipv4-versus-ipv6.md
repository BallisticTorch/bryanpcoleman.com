---
author: Bryan
date: 2019-04-11 21:14:06+00:00
draft: false
title: IPv4 versus IPv6
type: post
url: /2019/04/11/ipv4-versus-ipv6/
categories:
- Networking
tags:
- DNS
- IP
- networking
---




Internet communication would not be possible without the
Domain Name System (DNS). For humans to interact with computers, there is a
need for a translator that can translate human readable addresses into
addresses that a computer can understand and act upon. Thus, DNS is used to
translate computer readable binary into and from human readable IP addresses.
DNS takes the process a step further by having records associating IP addresses
to their respective common language addresses. The common denominator in DNS is
the Internet Protocol address, also known as the IP address. To put it plainly,
an IP address is a house number or a mailbox number and it identifies the
location to which, or from which, data is communicated.







Since September of 1981, the standard for identifying
network hosts has been IPv4, also known as Request For Comment (RFC) 791 [2].
The RFC document provides specifications for the Internet Protocol per
standards defined by the U.S. Department of Defense. IPv4, at the time of its
creation, was the fourth revision, or version, of the Internet Protocol. The
RFC established all aspects relating to network communication using the
Internet Protocol, including addressing and security [2]. IPv4 has been the standard
for network communication for more than 30 years, until now. Global IPv4
address availability is on the verge of becoming exhausted [3]. As a result of
the growth of the mobile device market and the emergence of the Internet of
Things, IPv4 addressing is becoming extinct.







The Internet Engineering Task Force (IETF), responsible for
making the Internet work better, approved RFC 2460, which is the Internet
Protocol version 6, or IPv6. RFC 2460 was approved in 1998 and introduced the
new standard for network addressing. Its introduction and eventual adoption as
the standard by which all networked device communicate will allow for 340
undecillion addresses to be available. That equates to 3.4 billion, billion,
billion IP addresses, more than enough for every person on the planet to have
4.8x1028 devices. While it is good to know that there is a solution on the
horizon to solve the extinction of IPv4 addresses, there are some differences
related to the integration of IPv6 into the IPv4 environment, and it all starts
with DNS.







## IPv4 Standard







The IPv4 standard uses 32-bit addresses in a dot decimal notation that looks like this: 






    
    <code>xxx.xxx.xxx.xxx</code>







The “x” is replaced by a number between 0 and 255 in each of the four sections (also called octets). IPv4 addresses are divided into five distinct classes, class A through class E. Each class has a different bit length that comprises the addressing of the network host. The class A IPv4 address uses the first octet, or section, of an IPv4 address for the network identifier, with the remaining octets reserved for host identification. The class C IPv4 address uses the first three octets, or sections, for network identification, with the fourth and final octet reserved for host identification. 







## IPv6 Standard







The IPv6 standard uses a significantly more complex address that is 128-bits in length, as opposed to IPv4’s 32-bit length. While the IPv4 address is explicitly decimal, the IPv6 address uses hexadecimal to represent an IP address. The format for an IPv6 address is 32 hexadecimal characters separated by a colon into eight groups of four characters. 









An example of what an IPv6 address looks like is as follows: 








    
    <code>2001:0db8:85a3:0000:0000:8a2e:0370:7334</code>









The IPv6 standard allows for a shortcut to reduce the length of the address visually by removing subsequent groups of zeroes and replacing them with a double colon. Using the example address above, it could be written like this:








    
    <code>2001:0db8:85a3::8a2e:0370:7334</code>









This is known as zero compression, where repeated groupings of zeroes are trimmed down and any leading zeroes are removed [1].









## DNS with IPv4 and IPv6







In DNS, the IPv4 address is configured as a host record, also known as an A record, and is used to resolve a host name, for example, domain.com, to the IP address of the server that supports that domain. 







DNS is also used to configure a reverse lookup for an IPv4 address so that a computer can locate the host of a particular IP address. By writing the IPv4 address backwards and adding “.in-addr.arpa” afterwards, a reverse lookup zone can be created. 







An example of an IPv4 address is:






    
    <code>8.8.4.4</code>







This is an IPv4 address that Google owns and is configured as a DNS A record. The reverse lookup for this DNS zone record would look like this:






    
    <code>4.4.8.8.in-addr.arpa</code>







The IPv6 record in DNS is known as an AAAA record, read aloud as “Quad-A”, and is used to map a host name to the IPv6 address [1]. The new IPv6 standard also introduces a new reverse lookup record for DNS, but its format is similar to that of the IPv4 standard. The IPv6 address is written backwards, just like in IPv4, but it is then followed by “ip6.arpa”. 







Using the address provided in the above IPv6 example, the zero compression must be removed first, and then the IPv6 address can be written in reverse:






    
    <code>4.3.3.7.0.7.3.0.e.2.a.8.0.0.0.0.0.0.0.0.3.a.5.8.8.b.d.0.1.0.0.2.ip6.arpa</code>









The reverse lookup zone in DNS is created automatically for IPv4 and IPv6 addresses when the initial forward lookup zone is created. 









## Summary







Although IPv6 looks complicated on the surface, it is meant to behave in much the same way as the traditional IPv4 standard. There are benefits to utilizing the IPv6 standard over IPv4, one of which has already been mentioned, and that is the additional IP addresses that will be available. Additional benefits include more efficient routing and packet processing, simplified network configuration, and security [4].









In terms of using IPv6 with DNS, the result is a smaller DNS table and more efficient assignment and interaction with network nodes. For systems and network administrators, the auto-configuration of IPv6 addresses is an improvement over IPv4, particularly because of IPv6’s use of a device’s MAC address as part of the IPv6 address.









While IPv4 and IPv6 share features and rules, it is the
scale of support that makes IPv6 the new go-to standard for IP addressing. The
enormous amount of available addresses in IPv6 along with additional benefits
like anycast, auto-configuration, and simplified IP assignment, ensure the
future of the new standard. Internet Service Providers are upgrading their
equipment to support IPv6, as are device and computer manufacturers all over
the world. In the next few years, IPv6 will be the new IP addressing scheme for
the Internet.







## References







[1] Horley, E. (2013). Practical ipv6 for windows
administrators. Retrieved from [http://common.books24x7.com.lib.kaplan.edu/toc.aspx?bookid=62121](http://common.books24x7.com.lib.kaplan.edu/toc.aspx?bookid=62121)







[2] Internet protocol. (September, 1981). Retrieved from [https://tools.ietf.org/html/rfc791](https://tools.ietf.org/html/rfc791)







[3] Li, Q., Qin, T., Guan, X., & Zheng, Q. (April 29,
2014). Exploring flow characteristics in ipv6: A comparative measurement study
with ipv4 for traffic monitoring. KSII Transactions On Internet &
Information Systems, 8(4), 1307-1323. doi:10.3837/tiis.2014.04.009







[4] Park, S., Jeong, J., & Hong, C. (July 18, 2012). DNS
configuration in ipv6: Approaches, analysis, and deployment scenarios. IEEE Computer
Society, 17(4), 48-56. doi:10.1109/MIC.2012.96



