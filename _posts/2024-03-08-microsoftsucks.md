---
title: "Isn't it strange how Microsoft tries to sweep vulnerabilities under the rug?"
date: 2024-03-12T23:29:01Z
categories:
  - blog
tags:
  - hacking
  - exploits
  - zeroday
  - microsoft
---
# Microsoft trying to sweep vulnerabilities under the rug?


tldr: microsoft is potentially hiding information about vulnerabilities that they know will cause public disrupt


Back in 2022 or 2021, when I first started dwelling in exploits and the sorts, I was asking my friend about them, and he's been around for a LOOOOONg time, like 13+ years of hacking.


Now, he was teaching me about zerodays and the sorts, just informing me about what was around at the time.

I asked him something along the lines of "How do they work!", and he just tossed me a private exploit, specifically one for Windows Defender. Windows defender gives all programs a "threat score" persay. If it's high enough, it gets flagged.

Good shit, nice system right? It SHOULD be good, but the issue was that you could set the score of apps before they've even ran. How this works I'm unsure, I lost the source because when I got it, I didn't know shit, so I was just like "The fuck is this" and did nothing. Now a year or two later, I start getting more fully into hacking, actually trying to find my own exploits. And I'm looking into the one he gave me to see if there was any mention of it, and there is none.

So, I start trying to find it again as I remember the file you had to reverse to find it, since he told me (Don't quote me on this, don't know if it was right)

The file in question was MsMpEng, which strangely enough has almost no documentation on what it does...

Anyways, here's a post about it. This is for the weird Microsoft Cloud bs, but it's on home devices too, but I believe you're unable to see it.


https://learn.microsoft.com/en-us/defender-cloud-apps/risk-score


Now, the funny thing is. This exploit got patched (apparently it got leaked), but when you try find ANY Microsoft disclosures about it, there's NOTHING. Not one trace of it.

Isn't it strange how they disclose other shit, but when it's something Like Windows Defender, which by the way, a lot of users trust, there's just no trace of disclosure?

Like, you'd expect **something**, like even if it was a watered-down slopfest?


Less of a major post, more of a "What the fuck Microsoft??".

I'll look into it more later, if I find anything I'll release a PoC.


Will be releasing actual articles about CobaltStrike soon.
