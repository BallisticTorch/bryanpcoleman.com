---
author: Bryan
date: 2019-03-15 15:14:16+00:00
draft: false
title: Facebook Outage a DDoS Cyberattack?
type: post
url: /2019/03/15/facebook-and-instagram-outage-ddos-cyberattack/
categories:
- Cybersecurity
tags:
- DDoS
- denial-of-service
- networking
---




On March 14th, Facebook, and another of their platforms, Instagram, were reportedly down due to some kind of outage. According to Kate O’Flaherty, a freelance cybersecurity journalist, [in an article written for Forbes](https://www.forbes.com/sites/kateoflahertyuk/2019/03/14/was-the-facebook-outage-a-cyber-attack/#29cb0dc95223), yesterday’s outage was the worst since 2008. There was speculation that Facebook had become a victim of a cyber attack, a DDoS attack, which would not be altogether surprising given the amount of flak they have received for data breaches and security issues over the last 18 months or more.







O’Flaherty stated that there was rumors and speculation running rampant on Twitter indicating the possibility of a DDoS attack, but a spokesperson for Facebook stated that it wasn’t the case. Nevertheless, the outage yesterday for Facebook (and Instagram) are lacking a clear explanation of what happened, but there is a more important problem here that this.







The problem here is the article’s and Facebook’s use of the term DDoS. This is a common problem in the tech industry wherein the term DDoS (distributed denial-of-service) is used interchangeably with DoS (denial-of-service) attacks. The only commonality between these two types of cyberattacks is that they both aim to interrupt the flow of traffic to a website or web-based service, but how each of these attacks is carried out is vastly different.







## What are Denial of Service Attacks?







Denial of service attacks attempt to take websites or web-based services offline by flooding the incoming network connection(s) with a variety of packets, overloading network and system processing, effectively taking a site or service offline by preventing access because of traffic overload. A denial-of-service attack is conducted from a singular device, using a single network connection, to flood a target network or system with packets of useless data. A DDoS attack is one in which the denial-of-service attack originates from multiple sources - multiple devices and multiple network connections.







These two types of cyberattacks are very similar in their results, but are very distinct in their methods. It seems to me that the speculation, the contributing author, and even Facebook’s spokesperson jumped to conclusions by using the term DDoS. Unless you have an IDS/IPS (intrusion detection system/intrusion prevention system) deployed and a team of network analysts reviewing logs in real-time, it is incredibly difficult to determine if a DoS attack is distributed. Therefore, it would behoove folks in the IT network and security industry to refrain from using DDoS as the go-to nomenclature when speculating, or in this case, responding to speculation, of a denial-of-service attack.







## DoS and CDNs







Attempting to perform a DoS attack on a social media platform like Facebook would be a daunting task. They will likely be using a CDN (content delivery network) with servers hosted in data centers all over the world. It is impossible to perform a DoS attack on Facebook and affect all of its users. It may be possible to affect users in a particular region with a DoS attack, but even then, it would be incredibly unlikely. Facebook would have multiple servers in a data center just for balancing the load of a given region, so a single device with a single network connection would be nothing more than an annoying gnat on a Sunday afternoon picnic.







Understanding what a DoS attack is and how ineffective it would be on something like Facebook, one could argue that this is the reason for the immediate jump to DDoS in both the Twitter speculations and the Facebook spokesperson response. However, it should be common practice to refer to denial-of-service attacks as just that, rather than escalate it to its distributed variety. It would go a long way to educate the masses, that’s for sure.







To effectively DoS Facebook or any other large corporate entity that uses CDNs, a very large botnet would be required. In fact, I would speculate that upwards of a million devices or more with stable network connections would be required to effectively perform a denial-of-service attack on Facebook. It would take quite a bit of research by the cyber attacker(s) to determine the various IP addresses used by Facebook in a given service region. They would then have to write a complex series of instructions for the botnet in that region to target all of the potential IP addresses of the systems serving up Facebook to the users of said region. This type of distributed DoS attack would be expensive, time consuming, and may still be ineffective for a targeted global disruption of services for the social media powerhouse.







## Summary







The effects of Thursday’s Facebook outage was world-wide, and if Facebook has a competent network and security team, they likely know that the outage was indeed not a DDoS attack. Nevertheless, the folks that speculate about such things should have some understanding of what a DDoS attack is and the undertaking required to pull it off. And those that respond to such speculation, including Facebook itself, should attempt to use proper nomenclature in response to such speculation.







Want to know more about DDoS attacks? Check out more articles here like this one: [https://bryanpcoleman.com/2019/03/16/dos-vs-ddos-whats-the-difference/](https://bryanpcoleman.com/2019/03/16/dos-vs-ddos-whats-the-difference/)



