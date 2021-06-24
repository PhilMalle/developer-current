---
title: Writeup - HTB - Templed
layout: post
summary: Walkthrough of Templed from HackTheBox.
author: fr3akazo1d
date: '2020-10-29 23:14:00'
keywords: Security, Templed, Cypher, Crypto, Challenge, HackTheBox, HTB
category: walkthroughs
thumbnail: "/assets/img/htb-images/templed-htb.png"
permalink: "/blog/templed/"
usemathjax: true
published: true
---


# General Information

| Platform | Room        | Date        | Difficulty | Tags                               | Time |
| --------- | ----------- | ----------- | ---------- | ---------------------------------- | ---- |
| HackTheBox | Templed    | 29.10.2020  | Easy       | Security, Templed, Cypher, Crypto, Challenge, HackTheBox, HTB | 2h   |

The next challange of the beginner path is a crypto-challange were we have to decode a cyper. 

We have to download a zip file from HackTheBox and extract the file. 

After extracting we got an png file:

![Scroll.png](/assets/img/htb-images/Scroll.png)

After some research i came accross the Templed Cypher. 

![templed-cypher.png](/assets/img/htb-images/templed-cypher.png)

So i had to figure out how the code is to decode: 

72 84 66 123 77 48 78 107 115 95 107 78 51 119 33 125

Decode the symbols of the picture. 

No this code looks like decimal. I open https://www.asciitohex.com/ and convert it to ASCII. 

And i got the flag for this Challange. 

Th4nks 4 R3ad1ng

Fr3akazo1d!




