---
author: Bryan
date: 2019-03-24 15:52:25+00:00
draft: false
title: Software Defined Networking
type: post
url: /2019/03/24/software-defined-networking/
categories:
- Networking
tags:
- networking
- SDN
---




You’ve just received a request from the development team that the testing virtual machine (VM) needs to “move” to the production environment network immediately to support faster deployment of tested and approved applications and updates. No big deal right? It’s a simple process of changing the VM’s IP configuration, updating some firewall rules in the data center, updating the local network, and do it all in the time the development team allotted during business hours. How many firewalls and routers do you need to update? Do you already have scripts in place that can do this for you, or are you going to do this manually? Is there enough bandwidth allocated to that network to support another system’s traffic? What about your documentation - how quickly can you get that updated? Let’s not forget your DR and BC plans too!







## Network Virtualization







Network virtualization is one solution to this problem. Rather than physically moving hardware around, potentially running into issues like not enough ports on a switch, network admins can take the virtualized approach to networked VMs. Network virtualization creates logical segments of a network making it easier for network admins to move domain-connected machines around or add new ones, virtual or otherwise. Network virtualization is essentially an overlay, or a tunnel, that allows two or more domain-connected systems to communicate without having to make changes to the hardware level of the network. Network virtualization runs on top of the existing network.







With network virtualization, admins can create virtualized routers, switches, firewalls, and even intrusion detection/prevention systems (IDS/IPS). Virtualized routers are really no different than their Layer 3 hardware counterparts, except they are wholly software-based. The software can be deployed on a commodity server, effectively turning that server into a router, of sorts, or deployed inside a VM that can be moved around on a whim. The same is true with the other virtual network components wherein the software-based devices will act the same way as their physical counterparts, only they are much easier to move around and manage.







Network virtualization is commonly seen in very large enterprise networks, data centers, and Internet Service Providers (ISPs). There are several benefits of virtualization, namely cost and efficiency. A physical firewall may cost several thousands of dollars whereas a virtualized version may cost one-fifth or less. There is also costs associated with personnel, down-time, and supporting hardware components. Down-time costs businesses a significant sum of money and physical changes on a network are time consuming and inefficient. Virtualizing network components in a network that demands frequent changes will solve a significant number of problems for network admins and businesses.







## Software Defined Networking







Software Defined Networking (SDN) is very similar to network virtualization in that networks are wholly software based. One key difference here is that SDNs are fully programmable, and you don’t have to have expensive routers and firewalls. Instead, a network need only to have switches capable of using an industry standard protocol such as OpenFlow, developed by the Open Network Foundation ([www.opennetworking.org](http://www.opennetworking.org)). Network virtualization creates tunnels, overlaying a physical network, changing the logical flow of a network. SDNs take the place of the physical network, to some degree, and separate the control plane from the data plane of a network.







Let’s say you need to move that VM discussed above, not because the development team requested it, but because you see that it is saturating its 1Gb connection. You’ve already verified that the traffic is authentic and there are no vulnerabilities or intruders on the line. You could take a drive to your data center CoLo to see if you’ve got any 10Gb links available and then move the link after-hours and be good to go the next business day. However, you’re looking at a significant amount of your time being sacrificed to make a simple change to improve the accessibility of the VM, and a significant cost if you’re paid hourly and your company pays for mileage and travel time.







What if you could log into a UI that allowed you to update the connection link from 1Gb to 10Gb with just a few clicks in a matter of minutes, in real-time, during business hours, without impacting the business, the VM, or the developers and applications using it? That is where SDN and its agility comes into play. Network admins can adjust traffic flow, optimizing the flow of network traffic in between the Application layer and the Infrastructure layer in real-time with no impact to business continuity.







## The Future of Networking







SDN and Network Virtualization are here to stay, and each have their place depending on their deployment. SDN will see more use in businesses over the next decade for two reasons: cost (encompassing hardware, personnel, and time) and management. Network administrators not currently in the loop of SDN need to get there, and fast. SDN will change the way networks operate and will change how network admins do their jobs. Imagine being able to focus on those network logs and immediately solve network connectivity issues immediately. Imagine being able to use the time saved with SDN by monitoring IDS/IPS systems or planning new ways to combat outside threats.







There will always be a need for hardware-based networking technologies, but management of those devices will become much easier and efficient as Software Defined Networking takes center stage.



