---
author: Bryan
date: 2019-03-16 19:51:19+00:00
draft: false
title: DoS vs. DDoS - What’s the difference?
type: post
url: /2019/03/16/dos-vs-ddos-whats-the-difference/
categories:
- Networking
tags:
- DDoS
- DoS
- networking
---




We use networks everyday, whether we are posting something on Facebook or Twitter from our mobile phones, catching up on the latest news in an online magazine, or binge watching our favorite shows on Netflix or Hulu. Networks are incredibly complex, yet for those in the know, they are all at once beautiful, intuitive, and a pain to manage, monitor, and protect. Networks serve as the backbone of every business, organization, government, school, and home. They facilitate the communication between dissimilar devices at a single location, up the street, across the country, and across the world.







## DoS Attacks







Networks use packets of information sent and received to and from binary addresses over hardware-based medium that are designed to facilitate such transactions. But they hide an ugly secret - they are prone to limitations and/or failure should they become inundated with requests and traffic that exceed their management capabilities, regardless of the validity of the requests and traffic. A denial-of-service (DoS) attack is best defined as an attack on a system that either limits or causes failure to that system, its operating performance, and/or its services. DoS attacks originate from a single computer over a single network connection, but the target of the attack can be another network, a network node such as a router or a firewall, or a specific system like a desktop computer or a server (i.e., database or web server). DoS attacks can even target operating systems, web-based applications, Voice-over-IP systems, alarm and physical security systems, and the list goes on.







The point of a DoS attack, generally speaking, is to disrupt or deny a service or services provided by a target, a web server for example. Corporations and governments face the most risk from a DoS attack, or rather, they did until network component manufacturers and the cybersecurity industries beefed up monitoring and mitigation capabilities. Technically, these entities can still feel effects from a DoS attack, but today most cyber attackers realize that the payoff is larger if they scale up the DoS attack, distributing the load of the attack across thousands and thousands of devices, effectively increasing the success rate and damage of a denial-of-service attack.







## DDoS Attacks







Distributed denial-of-service (DDoS) attacks are the latest iteration of service denial that corporations and governments have to fear. No single source will be the culprit in a DDoS attack as the attack will come from a variety of sources, making it difficult to intercept and prevent such an attack from occurring. The source(s) of a DDoS attack can even appear as legitimate traffic, as seen in the attack on Cloudflare in 2014 and the use of spoofed source addresses and a vulnerability in the NTP (Network Time Protocol). DDoS attacks are incredibly difficult to prevent, but they are easy enough to monitor for. However, monitoring a network for a potential DDoS attack has its own share of limits (personnel, finances, software, and hardware), and the end result would be the same: either you take your system(s) offline until the DDoS attack stops, or the DDoS attack takes your system(s) down for you. Either way, there is a significant impact to businesses and governments, often resulting in hundreds of thousands, if not millions, of dollars in losses.







With the culmination and rampant growth of the Internet of Things (IoT) and the inability of device manufacturers to consider security when designing, manufacturing, and selling these devices, cyber-attackers have found a plethora of devices they can bring into their botnets to wreak havoc on businesses, governments, and other institutions. In fact, that is exactly what cyber attackers have done with Mirai, Torii, and a number of well known and effective botnets. For the layman, a botnet is essentially a network of computers that have been infected by malicious software, controlled by a cyber attacker. Usher in “smart devices” like connected thermostats, light bulbs, refrigerators, and coffee machines, and all of a sudden the number of devices available to cyber attackers to gain control of quadruples, over night!







## Defenses Against DoS and DDoS Attacks







Although preventing such attacks from occurring can be expensive and complex, the competent network analyst, engineer, and administrator will at the very least use monitoring tools to alert them to the occurrence of an attack. Network monitoring tools can range from free to a year’s salary to implement, from the feature poor to the feature rich. Regardless of the financing limitations, network monitoring tools will allow for denial-of-service discovery. Many cyber attackers will stress test a target before launching their full scale assault, so a monitoring tool from Spiceworks, Solarwinds, or Nagios can help identify these scouting missions.







Interface monitoring tools, packet analyzers, and port scanners are also effective tools to monitor, configure, and secure a network. Establishing a baseline of network activity is required to effectively monitor and discover unusual activity and possible attacks. These tools can identify vulnerabilities that need to be battened down and assist in establishing a baseline from which networking personnel can be more diligent in discovering and mitigating most DoS and DDoS attacks.







Many Internet Service Providers (ISPs) offer DDoS protections, either added on to a business Internet service contract or included with an existing one. Working with an ISP on mitigation efforts will help organizations and governments to transfer some of the risks they face to the ISP, offloading some of the responsibility for discovery and prevention to their resources.







## Summary







It is important to note that relying on any one of these potential defenses against denial-of-service attacks can prove to be just as detrimental as the attack itself. Instead, it is important to use all resources and tools available, and this includes personnel, to reduce the risks of an attack occurring. The fact remains, at some point, an organization will fall victim to an attack - be prepared, or pay the price.



