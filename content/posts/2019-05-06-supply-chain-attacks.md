---
author: Bryan
date: 2019-05-06 19:12:14+00:00
draft: false
title: Supply Chain Attacks
type: post
url: /supply-chain-attacks/
categories:
- Cybersecurity
tags:
- cybersecurity
- network
- information security
---

A supply chain attack is a cyberattack that targets less secure elements of an organization, be it their third-party API integrations, remote manufacturing facilities, and specifically, weak networks and systems. The term “supply chain” often elicits thoughts of manufacturing processes and logistics, or the process of getting goods such as groceries from the farmer’s fields to the shelves of a grocery store. In cybersecurity, the supply chain refers to all of the above and more, including hardware and software that ends up in the hands of consumers, businesses, and governments.

## NotPetya

The goal of supply chain attackers is to infiltrate some portion of an organization’s supply chain resulting in malicious software sitting dormant in said organization’s distributed product. For example, the NotPetya ransomware that attacked and held hostage many financial markets in Eastern Europe was considered a supply chain attack. This is due to the hiding of malicious software inside Ukrainian-created accounting software, specifically a routine update that was pushed out by the software developer. Hackers had infiltrated the developer’s network and injected malware into one of the update packages.

The software, distributed all over the globe, was configured to automatically install updates (in most, but not all cases). As a result, thousands of computers were infected with NotPetya, bringing many pharmaceutical and logistics organizations down for several days. If you are interested in reading a ground-zero account of the NotPetya attack on Maersk, I highly suggest reading **Andy Greenburg’s** *[The Untold Story of NotPetya, the Most Devastating Cyberattack in History](https://www.wired.com/story/notpetya-cyberattack-ukraine-russia-code-crashed-the-world/)* in Wired Magazine’s September 2018 edition. This story will reveal how devastating and effective a supply chain attack can be and the disruptions it can cause.

## Barium

Andy Greenburg from Wired Magazine [wrote another article](https://www.wired.com/story/barium-supply-chain-hackers/) uncovering the hacker group known as Barium whose forte is supply chain hacking. The recent revelation of compromised software from computer hardware giant ASUS early in 2019 and the compromisation of Piriform’s CCleaner software in 2018 are the work of Barium. Mr. Greenburg points out that if Barium were hell bent on destruction, they could have exploited these supply chains more effectively and introduced ransomware rather than simply exploit weaknesses for the purposes of spying on governments, organizations, and consumers.

We all should be thankful that Barium, a Chinese hacking group, relegated themselves to espionage attacks rather than destructive ones. This is not to say that another hacking group couldn’t combine Barium’s effective supply chain attacks with ransomware and wreak havoc on Internet of Things devices, Microsoft Windows systems (still the dominant operating system for personal computing), or some other far reaching and ranging population of the tech industry.

## The Cure

Advanced Persistent Threats (APTs) are the bane of every security professional’s existence, a nightmare that must be lived with every waking and sleeping moment. APTs are difficult to detect as they are designed to lie dormant within a computer system or network until a pre-programmed time of execution. They are designed to remain stealthy, hidden away from prying eyes, and this includes poorly configured intrusion detection/prevention systems and anti-virus software.

APT prevention begins with employee training and ends with penetration testing, with a healthy dose of access and administrative controls in between. Cyberattackers capable of deploying an APT on a network got there because access controls were poorly implemented and administrators had poor judgement in patch and version control, effective firewall configuration, and effectively configured network protection tools like IDS.

## Cure for the Consumer Market?

Consumers often pay the heaviest price where cyberattacks are concerned. It is their data that is stolen from organizations that do not have effective security controls in place. If organizations and governments effectively secure their networks and systems, then cyberattacks will be less likely to happen. Well, that’s the idea anyway, but cyberattackers are smart - really, really smart.

In the case of supply chain attacks, if they are able to plant malicious software early in the supply chain, the final manufacturer or software developer will have no idea it is there and push out their products for consumers to use.

As is often the case, cyberattackers take advantage of the disparity between countries with respect to laws and governance, and it is this that allows them to infiltrate the supply chain and truly be successful. Consumers who buy the latest smart gadget for their home may be unaware that firmware on one of the computer chips inside the gadget has been compromised.

Lo and behold, months or years later, their new gadget becomes part of a botnet that targets some other unsuspecting organization resulting in the billions of dollars in damages and the theft of millions or billions of consumer data.

## Conclusion

I have [written software](https://bryanpcoleman.com/code-and-development-projects/) to automate things I do and I have written software for the fun of it. I’ve incorporated APIs (application programming interfaces) and libraries from third-parties to get those projects and tools in my project. How did I verify those libraries and APIs were clean, free of malicious software? I didn’t, because I couldn’t.

Often, source code isn't available for review because many libraries and APIs are closed source. It is also because I lack the knowledge to parse the contents of the code of these libraries and APIs.

So how can consumers, organizations, and governments know the software and hardware they create or purchase is clean? I honestly don’t know, at least for the consumer side of things. There are processes to follow and tools that can be used to detect malicious code inside software or hardware organizations and governments acquire that is to be used as is or incorporated into another product.

I suppose the only real answer to this question is: **_trust_**. Everyone has to trust what they purchase or use, trust the companies that provide the service or product, and hope that if there are supply chain attacks, everyone can bounce back quickly and efficiently.