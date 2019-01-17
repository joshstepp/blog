+++
title = "The Real Cybersecurity News: The Ukrainan Power Plant Attacks and Why You Should Care"
description = "Recent media coverage has been covering noise, but we need to focus on the signal"
tags = [ "thoughts","infosec", "cybersecurity" ]
date = "2017-01-21"
categories = [
  "Thoughts",
  "CyberSecurity",
  "Infosec"
]
slug = "realcybernews"
+++
<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/cybericsscada.png">


Recently, there has been an overwhelming amount of discussion over WhatApp’s non-existent “Government backdoor”, which can easily be debunked with the following statement:

*If Facebook wanted to allow any government to have a back door, they own the code base, they could just code one in. You wouldn’t know it. Additionally, the end points are still soft, you have to de-crypt the message to read it, which provides a much easier attack vector.*

*This is the result of a media outlet rolling with a story from a salty bug-bounty researcher and exciting an under-informed public over nothing important. At least Signal is getting some PR out of this. Good for Signal (which is a decent messaging app, it’s open source, secure but does have some hiccups, especially with late messages and attachments).*

*Furthermore, pushing this narrative urges people who need end-to-end encryption to move to a more convenient way of communication (because Signal isn’t widespread) which is often times SMS, a less than secure protocol. So while you may think it is important to encrypt your Friday night plans so big brother doesn’t know about your first world problems, others are at a much bigger risk.*

## The Real Cybersecurity News

In the meantime, the Ukraine has been hit with yet another cyber-attack disrupting their electric infrastructure. The first of which occurred in December 2015 through a sophisticated, multi-stage attack that consisted of custom firmware, spear-phishing e-mails, malicious Microsoft documents and telephone based denial of service attacks. The truly alarming part of this equation, besides the impressive amount of attack vectors used, is that the attackers performed reconnaissance of the network for an extended amount of time to properly understand the system, as these systems often times use propriety protocols or dated technology stacks. This is a major indicator that the attackers are disciplined and experienced.

The most recent attack was on a transmission station, and while there was a disruption of service, the damage could have been much worse according to initial reports. What this implies is that this particular attack was a demonstration or testing of a capability, not an actually attack for a desired strategic effect.

### What this means:

You are probably saying to yourself, “I live in America (or Europe, or where ever), so this doesn’t matter to me”…. Except ICS/SCADA systems are designed very uniformly across the board. The main purpose behind these system is availability. They are designed to be uber-reliable and to provide the service at all times with high efficiency. Additionally, these systems are older, and at that time, security was the least of their developer’s concerns.

This can be observed by spending 10 minutes browsing <a href="http://www.shodan.io">shodan.io</a> and seeing how many systems face the internet wide open.

So while there may be slight differences (models, protocols) between components like the Human Machine Interface (as the name states, the terminal for users) and Programmable Logic Controllers (components that do a specific action… i.e. open a valve) in California and in the Ukraine… they are still serving the same purpose.


### Think of it like this:


*Your keyboard is made by Dell, mine is made by Apple. So while they are technically different, it wouldn’t take much effort on anyone’s part to understand how the other transcribes text to screen.*


Lastly, with the growing concern of a “Cyber 911” occurring, this is a clear indicator of capability for a high valued effect. Although, judging by the amount of attention it is getting, no one really cares until it happens.



Further reading about the most <a href="http://motherboard.vice.com/read/ukrainian-power-station-hacking-december-2016-report">current attack</a> and the <a href="http://www.nerc.com/pa/CI/ESISAC/Documents/E-ISAC_SANS_Ukraine_DUC_18Mar2016.pdf">December 2015 attack</a>.


Josh Stepp
