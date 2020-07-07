---
title: "Coding and Development Projects"
type: post
date: 2018-07-05T18:25:49-04:00
url: /projects/
image: /images/2020-thumbs/projects.jpg
---
## Intro

I have long been interested in programming but as my career began in networking and is now focues on system administration and engineering, I haven't realized my interest in programming as of yet. What I mean to say is that most of my time is spent learning the technologies and solutions for my current career. That leaves little time to pursue programming and development outside of base hobbying.

On this page are programs I've written to solve problems or perform a task, with the exception of the Book Catalog below. The Book Catalog, well, it was designed to solve a problem, but it is of a personal nature. And although it is about 70% complete, I haven't touched it nearly a year, if not more. I wrote it in the languages that I am most familiar with - C# and SQL.

However, in re-developing this website using Hugo, markdown, YAML, and TOML - I've found there are other things I'd really like to learn, from a development aspect anyway. Given my past education and my current career, I think I can get into development by focusing on languages and development that will best suit my current job role(s). That said, I'll begin with Python and see where DevNet can take me. Enjoy the programs below, if you'd like.

## Book Catalog (C# and Microsoft SQL)

This project is personal. I wanted a way to organize the hard copy and digital books I own outside of [www.goodreads.com](https://www.goodreads.com). That site is good, but it lacks some features I wanted, and some of the features [www.goodreads.com](https://www.goodreads.com) has are antiquated at best.

The [Book Catalog](https://github.com/BallisticTorch/Book-Catalog) repository on my GitHub has all of my code for the Windows Form application I created. What you won't find is the SQL database, but from the code, one can infer the table setup and values.

[See it here.](https://github.com/BallisticTorch/Book-Catalog)

* * *

## Domain Testing against IIS Bindings (C#)

In a previous role, I was responsible for not only IT administration, I was also responsible for managing client domains (3,000+). Not every domain for every client was managed in the company's GoDaddy account, meaning that client's had complete control of their domain, including configuration and renewals.

We would often find out too late that a domain had been mis-configured (or reconfigured) or had expired. To ensure we had timely and updated information on all domains, both client and company controlled, I wrote this program that tested every domain (www and .) listed in IIS bindings against the IP address these domains should be pointing to. An email would be sent to me using SendGrid from each server with a list of the domains that failed to pass the test of where they were pointing. This allowed me to notify CRMs that their client's domains were not displaying the site we built, while providing them the necessary information to notify the client of why.

Here is the code for the [Domain Testing](https://github.com/BallisticTorch/DomainTesting) program.

* * *

## CSV File Comparison (C#)

In the same role as described above in Domain Testing, we were updating our CRM software, Salesforce, with a new feature. This feature added a domain tracking item to the Opportunity and Account screens of each client. We were able to list however many domains a client had and indicate whether the company or the client managed (controlled) them.

To update the existing clients in Salesforce, I felt it wise to take an automated route rather than waste 2-weeks of company time manually visiting each client account, comparing notes and domain registrar information, and updating records accordingly. Instead, this [CSV File Comparison](https://github.com/BallisticTorch/CSV-File-Comparison) program, adapted from others found on the web, compares the CSV output file from Salesforce with a CSV output file from Godaddy and return only those domains that are not present in the GoDaddy file. This told me that these were client managed domains. Using another program I wrote that trimmed the Salesforce CSV with these results, I had two files - one for client-managed, and one for company-managed domains. I provided these two files to the Salesforce Administrator who then automatically updated the information in Salesforce for each client.

[See it here.](https://github.com/BallisticTorch/CSV-File-Comparison)

* * *

## AI Computer Monitor (C#)


This project was done for fun, and is wholly incomplete. Several years ago, I had created a program that displayed vital PC information - CPU and GPU temps, HDD temps, RAM utilization, HDD activity, etc. Sure, Windows has the Task Manager, but I wanted a small "widget" of sorts that hung out on my desktop and providing real time information - all the time.

A few years went by and I learned of the Speech Synthesis library and decided it would be nice to upgrade my earlier program with speech alerts for when specific criteria are met - i.e., high temperatures, high RAM utilization, HDD capacity limits and utilization, etc. I've got the majority of this [AI Computer Monitor](https://github.com/BallisticTorch/AI-PC-Monitor) program written, but haven't touched it in a couple of years. May do so in the near future.

[See it here.](https://github.com/BallisticTorch/AI-PC-Monitor)