---
title: "How to ACTUALLY get started in Hacking."
date: 2024-03-28T05:22:21Z
categories:
  - guide
  - beginner
tags:
  - hacking
  - guide
  - tutorial
  - beginner
  - pen-200
  - pdf
  - resources
---
tldr: teaching ways to learn hacking, resources and whatnot.

# The REAL way to learn true Hacking.

"Hacking" is generally a cringe word, but it's the best one to use here.
Most people assume Hacking is just `git clone`'ing a Python script, and woahhh, suddenly you're Mr. Robot.

In reality, this is *somewhat* true, **however** in practise, this won't work when you actually get a job in Cybersecurity.

Or maybe you're gonna be blackhat. That's not really a issue, just don't be an obnoxious comkid, threatening people with their IP (Ironic, I know.)

Now, you may be thinking *"Oh, this is great and all but... how do I even start"*.

People think it's hard to start, it's not.
But do note. Hacking is not for everyone. If you expect it to be easy, or something you can just not put that much effort into, **you are mistaken, and you will not do well**.

Hacking takes months to even get reasonably good at, and that's if you're spending countless hours a day learning.
Also, it *can* be pretty pricy, (but I'll go over how to learn for free, but it'll involve sailing the seven seas).

First of all, you need to decide what **type** of Hacking you want to learn. Yes, there are multiple, and yes some are more fun and rewarding than others.

You can do multiple, but be warned, the more you know the less you know. 

Some of the MAIN types.

### Web Hacking
**Web Hacking** involves exploiting Web Applications, as in Websites. The main goal usually is to try and obtain a **shell** (Commandline) on the site, but often a **threat actor** will settle for **dumping the database** if they can't get a shell, which basically exposes all of the users information. In the modern day, the passwords are hashed, but often this can be broken with relative ease.

### Server Exploitation
The **most fun type** in my opinion. Things like exploiting Active Directory (Windows, but for large companies), pivoting between machines, escalating privledges, stuff like that. Do be warned **pivoting is hard to keep track of.** Imagine playing Chess with 6 boards at once. 
This type is probably one of the hardest types to learn, but also the most important, unless **you're in a team**, which I will cover soon. It will GREATLY help.

### "Wireless Hacking"
This is mainly about **hacking WiFi networks**, but I believe this isn't limited to just WiFi, I'd personally consider this a subgenre of Web Hacking (but not really).

One of the main points of this is **snooping for credentials**. However, this type is slowly being phased out as Network Security gets better. It got essentially erradicated after HTTPS became the standard in around 2018, at least that was when **almost everyone switched**, and while there's techniques to still snoop unless you'd like to go through the effort of doing a MitM, which is in itself not that effective.

Plus, unless you wanna go do this in the wildand go to Federal Prison, you'll probably never get a chance to exploit this in the wild.

### Red Teaming
My my, **where to begin with this.**, Red Teaming is **a lot to cover.** 
This includes **literally everything**, including **physical security**.
Red teaming is fun, I'd say the most enjoyable type of hacking. It's quite literally blackhat hacking, but it's legal. 

You'll be doing stuff like **phishing**, **malware development**, **physical audits**, other stuff like that. By the way, Physical audits are insanely fun. 

Now, this type is the hardest to learn **if you wanna do it good**. You'd need to learn **Wireless Hacking**, **Server Exploitation**, **Social Engineering** and much more.

But here's the thing. 99.9% of Cybersecurity jobs are Red Teaming.
But you dont' need to know **all of this**. This is because you will often be working in a group/team. Which we will be getting into soon.


# The Hats of Hacking.

Now, if you've watched any videos about hacking **(bad idea)**, you've probably heard terms like **White Hat hacking** and **Black Hat Hacking** thrown around a lot.

There are many **that are not "official" persay**, I will not be going over theese. There are only 3, technically 4 types.

**Please do not make this your entire personality**, we do not need more people like **IPHacker**.

![IPHacker](/assets/images/iphacker.png)

Anyway.
The three hats are

### White Hat Hacking.
This includes people like **Red Teamers**, Actual **Cybersecurity Researchers** and generally, people who do not partake in illegal hacking. This is what the majority of Hacking platforms teach you to be.

### Black Hat Hacking.

Now, this is **strictly Illegal Hacking.**, mainly done for just profit, or just for the lulz. 99% of "Blackhat Hackers", do not know what they're doing, **but that 1% that does is terrifying**. I wouldn't reccomend this, not because it's illegal, but until you actually know what you're doing because

- You'll make 0 profit
- You'll just look stupid

### Gray Hat Hacking.

Now, the more **advisable** site. Gray Hat Hacking is both illegal and legal. You can work a legal Cybersecurity job or whatnot, or do BugBounty (will get into it later), and do really whatever you want. You'll also do illegal stuff though.

This is type type **I would advise if you are going to do illegal things and don't care about the consequences**. Let's be real, the best way to learn is just poking at things in the wild. You can't do that legally, CTFs are unrealistic usually, and bugbounty programms already have everything found. Obviously don't go dump a childrens hospital, but if you're gonna poke around at webapps, while going for legal jobs and certs, this would be **Grayhat**.

### NationState.

Theese are **blackhats** but it's legal as they are **paid by Governments to do it**. Not much is known about them, which is the entire point. Just know, you'll have a **very** bad day if you poke the wrong bear.

Enough talking about the hats, let's move onto the more important stuff.

# Where you can learn

The main platforms are

- HackTheBox
- HackTheBox Academy
- TryHackMe
- HackThisSite

I will be referring to theese as HTB, HTB:A, THM and HTS.

I'd advise starting with THM, as HTB is for CTFing, which while a good way to learn, it's not the best for beginners.
HTB:A on the other hand is great, better than THM in my opinion. However, it comes at a **extortionate cost** for what you learn, however you do recycle some of your **on-site currency**.

YouTube videos are generally a bad way to learn. They are overly long for what they teach.
I'd advise **joining a community** to learn too. There are many places like this, but the best one in my opinion is on Discord. I won't name a few, but if you'd like to join one, come join https://discord.gg/malware. Please do note, we aren't too friendly to beginners, and we have manual verifications, **however if you state you are from this blog, I will allow you in without verification, as we do like beginners who we know are actually trying to learn**.

Please do note, the Hacking community can be absurdly toxic, so I'd advise staying in the "legal" servers. The ones targetted towards Blackhat are very hostile, and generally intolrable to be around.

Now, if you're saying **"But Stealth I have no money???"**, Simple. Sail the Seven Seas.
Knowledge, specifically for Hacking has became at a EXTORTIONATE price in the modern day. The field is cramped, lots of people wanna learn but there's not many spaces.

A good way to learn is PDFs. I reccomend reading the PEN-200 PDF. It has almost everything you'll ever need. 
Specifically, [theese videos](https://dl.tgxlink.eu.org/dl/66050cf91f1f7b34b653d0e8), and [this PDF](https://dl.tgxlink.eu.org/dl/66050d011f1f7b34b653d0e9), but please do note **when Pirating content, you will be learning less and hurting the industry. You won't be able to use the labs.**

# Joining a Team.

A great way to learn is joining a Team with people who know more than you, or learning with your friends.
This also lowers the load on you, as you won't be the one learning everything alone.
Please don't rely too much on this though, **as you may miss critical knowledge**.

A great insentive is **Team Rankings** and **Team CTFs**
On platforms like HackTheBox, there's Team and Country leaderboards. Theese are good to keep you insentivised because you'll want to rank up. It's good shit.

# Effective Learning Strategies.

Your **brain** needs time to procces knowledge.
Now, while **slamming data into your skull** will work, in the long term you'll forget.
Obviously eventually while learning Hacking, you'll go like **40+ hours** at once CTFing or learning, which is perfectly fine if it's once every few weeks. But **do not** do this daily. Your brain will start to overwrite previous stuff you learnt.

You need to **practise daily**. The Cybersecurity industry is ever changing, you can't learn once and be a pro forever. You'll forget stuff, beacuse think about it. **Your brain is not meant to remember 300+ commands and 50+ exploit techniques**.

If you're using HTB, a good insenstive to play is **HTB Seasonal**. A really fun way to learn. Games like R6 have Ranked right? You get given a rank based on your performance.

Now, **Cybersecurity has the same**. A box is published every 2 weeks, a season will last a few months. Doing theese machines will give you **rank points**. Now you maybe saying, "is this just useless virtual internet points". No! They give you Giftcards if you do well enough. This is useful because **if you're broke you can get free HTB:A and Vip+ and whatnot**.

Make sure you **take notes**. I have only twice in my years of learning used my notes. But this doesn't mean anything. Your notes aren't meant to be read. When you just read something, most of the time your brain will forget it. This is why in school, you're made to use the things you learn, it **makes it stick in your brain**.
As such, you can take notes.

I'd advise using **Notion** or **GitBook** for this.
Also, **take notes while you do CTFs**, you can publish them as Writeups and get +rep on HHacking sites if people like your stuff.

# The End...?

**Thank you for reading.** This is just a basic overview. I will be creating a highly detailed version soon, that will go into more "advanced" stuff. This is just a introduction, but the next post will be talking about **Carreers in Cybersecurity**, **Advanced Types of Hacking**, **Malware Development** and **Doing your first CTFs.**

When I publish that, it'll be linked **here**.