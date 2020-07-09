---
author: Bryan
date: 2019-04-29 13:19:56+00:00
draft: false
title: Encryption and Data Breaches
type: post
url: /encryption-and-data-breaches/
categories:
- Cybersecurity
tags:
- data breaches
- encryption
- information security
---

*This is a slimmed down version of an essay written in early 2017 by Bryan for his Master of Cybersecurity degree at Purdue University.*

***

Every department store, clinic, bank, or website a person interacts with involves some form of storing of personally identifiable information. It is common for everyone to trust the organizations with whom they do business, accepting a certain level of risk by allowing those organizations to store and use their personal information. Unfortunately, data breaches are becoming as common as traffic accidents, calling for improvements in every facet of cybersecurity, including but not limited to, the encryption of stored data.

Encryption is not a new technology, but the idea of encrypting stored data is gaining relevant momentum. The focus of this essay is to explain encryption and the idea behind encrypting stored data, whether it is a file server or a database. Real-world examples are provided and discussed, concluding with expert testimony and this writer’s conclusions.

Data breaches are becoming too regular of an occurrence. Each day brings forth a new revelation of another attack on entertainment companies, banks, health care systems, and governments. Meanwhile, information technology departments the world over are upgrading their infrastructure and their personnel to put in place cyber protections to prevent such data breaches from occurring. While it is common place to throw intrusion detection and prevention systems at a network and add a couple of educated warm bodies to monitor those systems, it should be known that until a revolution in cybersecurity happen, data breaches will still occur with some regularity.

In June of 2015, the U.S. government suffered from a serious breach affecting several databases containing personally identifiable information for several million federal employees. Experts who advise the government claim that a number of government agencies were not following best practices, including updating computer operating systems and networking infrastructure. Regardless of the reasons for the breach, these same experts began making recommendations that includes encrypting stored data. Commonly referred to as data at rest, stored data runs the risk being target of outside and inside threats.

Ideally, all data should be encrypted to prevent the unauthorized viewing or theft of data. Will this prevent data breaches? It remains to be determined, although encryption may prevent or thwart outside attackers from viewing sensitive information, encryption does little to mitigate the insider threat. What follows is a brief introduction to encryption and data breaches as well as a brief analysis of the present use of encryption. Encrypting data at rest will be discussed in the section that follows. Finally, this paper will conclude with this writer’s thoughts on data at rest encryption.

# Encryption Basics

Encryption has a long and varied history dating back to several thousand years ago. Using cryptography, also known as the art of writing in code, secret messages were sent by empires to their allies, armies, and holdings. These simpler secret messages, often created using a letter-substitution system, could only be decoded by the recipient if they had the secret key. Eventually, encryption began using mathematical ciphers to encode messages, many of which evolved into algebraic formulas called algorithms[4]. In the 21st century, encryption refers to the manipulation and conversion of electronically stored data into a form that is unreadable by the human eye. Although not so different from the encryption used in classical times, the power of today’s computer systems can quickly break most ciphers from those eras.

### Lucifer

In the 1970s, IBM released the first reliable encryption method for public consumption known as Lucifer[2]. This encryption standard worked by using a block cipher, a method of taking a chunk of data and encoding it at one time rather than encoding each bit. Lucifer serves as the foundation for most modern encryption methods in use today. Other ciphers existed at this time, including the once popular stream cipher, which encoded chunks of data prior to transmission over wireless networks. Unfortunately, each of these ciphers have several weaknesses that can be exploited by any modern computer in a matter of minutes or hours so are not viable methods of protecting data.

### Encryption Goals

The goal of encryption is to prevent the unauthorized viewing of data regardless of the state of said data. When information is stolen or viewed without authorization, that data is said to have been a victim of a data breach. Such breaches occur on a regular basis and include outside and inside threat vectors. Examples of major data breaches include the example in the introduction, the Sony Entertainment company hack of 2010, and most recently, the release of the stolen database of Yahoo! email addresses and passwords from a hack in 2013. Each of these are examples of outside threats compromising networks and stealing stored data. What about insider threats? Certainly employees of organizations and governments can’t possibly be considered a threat to stored data, right?

### Insider Threats

Insider threats are not always malicious and are often accidental. In 2006, a hospital in Detroit suffered a severe data breach when a laptop was stolen out of a nurse’s car[5]. That laptop contained information for over 28,000 patients of Troy Beaumont Hospital, including social security numbers, insurance information, and of course, names and addresses[5]. And perhaps the most notorious case is that of Edward Snowden, who in 2013 copied and leaked classified information without authorization to a whistleblower website. While the ethics and details of this case will not be discussed here, it was Mr. Snowden’s intention to release important information to the American people, information he deemed worthy of their attention. Regardless of the reasoning, his actions have become the most important insider threat case to date. Whether an insider threat is accidental or malicious, it is just as important to consider alongside outside threat vectors and the need for encrypting data.

When speaking of encryption, most information technology professionals will queue up images of Internet-related transactions involving the exchange of information over a secured platform. In fact, many people will think specifically of VPN tunnels, Wi-Fi security protocols, or encrypted email applications. Many IT professionals will not even think of encrypting data sitting in a database or on a file server. There are several complexities involved with encrypting data at rest, chief among them is ease of access by authorized personnel. Rather than encrypt the stored data, IT professionals seek to secure the file system, database, network, computer system, and even physical security like offices and network closets[1]. Although every one of these security measures does a great job, collectively, in protecting data, these measures are not resilient enough to keep out the most persistent threats. As witnessed in the examples provided, secure networks and systems are still penetrated, so it is clear to see that traditional security measures are not enough to prevent data breaches and protect stored data.

# Data Breaches and Encryption

The weakest link in any network is the user – the hourly employee, upper management, and even the users employed in the information technology department. Cybersecurity education and continuous training are necessary to ensure an equal understanding of vulnerabilities, processes, and protocols by everyone in an organization[1]. Through the development of a culture of security and involving all personnel in the development of that culture, organizations stand a greater chance of combating data breaches[1]. As previously stated, the goal of a data breach is to obtain information, preferably, to an attacker, to obtain personally identifiable information. If users are trained on social engineering and phishing scams, and understand the policies and protocols when handling the organization’s data on-site and offsite, then what is the next step for protecting data at rest?

All encryption possesses flaws, specifically due to the human element involved in creating them. According to McCarthy, “secret writing that baffles investigation” is very difficult to invent[4]. Modern encryption involves an algorithm that is comprised of three more mathematical algorithms – an algorithm to generate encryption keys, another to encrypt a message, and a third to decrypt the message[4]. This sounds convenient enough for sending emails or transmitting data over a VPN tunnel or wireless network. But this process is not a viable solution for stored data.

### Healthcare Industry

Let’s look at the health care industry for a moment. According to William Tanenbaum, head of the Health Care IT practice at Arent Fox LLC, “strong cybersecurity” is not an option, but a requirement for health care institutions[6]. He further implies that medical records are more sought after than credit card numbers. Why would that be? A medical record contains names, addresses, and social security numbers – every key piece of information an attacker needs to assume a persons’ identity. A credit card typically has a set spending limit, but with a name, address, and social security number, an attacker can open multiple credit accounts using the victim’s identity. The attacker is rewarded many times over by obtaining these key pieces of information, more so than hacking a bank account or website. Tannenbaum suggests that hospitals should establish rules for accessing data based upon the national institutions who regulate health care institutions like HIPAA[6].

Returning to the incident in 2006 involving the theft of a nurse’s laptop with stored patient data, what rules could the hospital have put in place? Policies such as not permitting the taking home of organization property or network policies that deny the downloading of patient data to another device sound like reasonable measures of security. The question is, why wasn’t that data encrypted? All too often the answer is encrypting data at rest only keeps the honest people out. In truth, had the data been encrypted on the laptop, the theft of 28,000 patient medical records would have been in vain[5]. Even if the Detroit hospital did use encryption to store data locally, a user who downloads that data to another device must decrypt it[5]. If the data is not re-encrypted once on the new device, the data will now be at risk.

### Equipment and Data Theft

Theft of laptops is becoming a normal process for data thieves. It is far easier to steal a laptop than break into a network and its databases[3]. Another incident in 2012 involved the theft of a health care institution’s laptop from an employee’s home, resulting in the theft of over 9,000 patient medical records. The theft of physical devices doesn’t just affect the health care industry either. In 2006, a laptop and external hard drive containing the birth dates and social security numbers of millions of military active-duty and veterans disappeared while in secure custody of the Department of Veteran’s Affairs, specifically a single data analyst.

These examples call into question the benefits of encrypting stored data. On the one hand, the data stolen in the examples provided could have proved useless if the information had been encrypted. However, in the case of the stolen laptop in 2006, the data was encrypted, but the encryption key was stored on the laptop along with the data[5]. A lost or compromised encryption key does more harm than good in situations like this, and as Miller and Tucker point out, encryption software is not effective at preventing the unauthorized access of encrypted data by insiders[5]. The same key that was used to steal the patient records from the laptop is the same key the nurse used to put the data on her laptop. While she did have authorized access to the information, she ultimately gave unauthorized access to the thieves.

# Summary

Preventing data breaches poses some serious questions, and the theft of data poses a serious threat. Determined attackers will get the data one way or another, no matter how good a network is at preventing it or how secure stored data is. Encrypting data at rest will not prevent data breaches, and in fact, may encourage thieves to try different avenues to get the data by targeting personnel directly. As previously stated, the weakest link in any IT infrastructure is the user. The user is the human element, the part of computers and networks that is impossible to calculate and take into account.

Miller and Tucker advise that encryption works well only when an organization uses the strongest encryption available, protects the encryption keys, institutes policies for user training, and has strong role-based access control[5]. In the case of the health care industry, regulatory compliance in combination with good network systems means effective protection against data breaches[6]. Determining access roles for health records and other sensitive information should be the top priority of any organization, including using encryption, role-based access controls, and identity verification[1]. Encrypting stored data is among several means to protecting against and potentially preventing data breaches[4]. Among these many experts is a common theme – data encryption is not a means to preventing data breaches.

Encryption is one part of the overall picture to securing data. A well-rounded infrastructure that includes network security, intrusion detection and prevention systems, role-based access controls, data at rest encryption, and user training will significantly improve the odds of protecting data from theft. It is not possible to reduce the odds of theft to zero. For that, a revolutionary leap in network security and data protection will be necessary.

##### References

[1] Genes, R. (2016). Code cyber: Preventing breaches at hospitals and health care practices._ Journal of Health Care Compliance_, _18_(3), 13-18

[2] IBM. (n.d.). _Cryptography for a connected world_. Retrieved October 8, 2016 from [http://www-03.ibm.com/ibm/history/ibm100/us/en/icons/cryptography/](http://www-03.ibm.com/ibm/history/ibm100/us/en/icons/cryptography/)

[3] Keane, J. (2016) Why stolen laptops still cause data breaches, and what’s being done to stop them. _PC World_, 48-50

[4] McCarthy, H. J. (2016). Decoding the encryption debate: Why legislating to restrict strong encryption will not resolve the “going dark” problem. _Journal of Internet Law_, _20_(3), 1-39

[5] Miller, A. R., & Tucker, C. E. (2011). Encryptions and the loss of patient data. _Journal of Policy Analysis & Management_, _30_(3), 534-556.
Doi:10.1002/pam.20590

[6] Tanenbaum, W. A. (2016). IT systems put security into health care cybersecurity. _Journal of Health Care Compliance_, _18_(4), 21-26