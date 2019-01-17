
+++
title = "Calm Down, It's Just DNS"
description = "That IoT bot-net attack on Dyn isn't going to melt the internet"
tags = [ "thoughts","infosec" ]
date = "2016-10-04"
categories = [
  "Thoughts",
  "Infosec"

]
slug = "itsJustDNS"
+++
 

Last month Dyn, an “internet performance management company” or a DNS provider, was attacked by what looks to be some flavor of the Mirai botnet. If you remember, the Mirai source code was dumped after the original users spread it to get rid of some law enforcement pressure. Furthermore, this botnet targets weak security in the form of backdoors/passwords put into the firmware of “internet of things” devices, like webcams and DVRs.  Essentially you have a weaponized Zergling rush of IP cameras that are never going to be patched by the users which will remain in service until the screws holding them in rust, and the unit falls from the ceiling forcing the user to buy another one.


On the other side of the coin, you have regulators, lawmakers and normal users freaking out because these devices “shut down the internet” which simply is not the case. What we have here is three fundamental conundrums that need to be addressed.


**DON'T PANIC!** If unsecured crappy machines were going to take down the internet, they would have during Microsoft XP/ME days. Adding to that, DNS, in simple terms is a phone book (yes it does other stuff as well), not a critical service like http/https.  


*there has been speculation that this was some state sponsored test, my response to that is why would someone “test” a capability like this publicly? Highly unlikely*


**DON’T BE STUPID!** We know how to fix this problem, but yet we don’t!  Seriously, it 2016, let's not hard-code credentials just to make the testing smoother. Additionally, if you are a HUGE, multinational company that relies on up-time ( Availability for you C.I.A. Triangle folks) to make money, why limit yourself to one DNS outlet? I don’t know all the motives but my speculation is that people from point three (keep reading) decided it would save them a marginal amount to outsource their DNS to Dyn. In doing so, that transferred their risk in favor of not controlling their own redundancy. When your single point of failure fails….. Well we saw the outcome.


**RETIRE!** Old people who don't know anything about technology are still making the rules. In my opinion, this is the most serious pandemic we are facing. This isn’t meant to be political or partisan in any way, but considering our candidates this year, are over 70, we are handicapping ourselves. Now consider how many 70 year olds you know that can operate an iPhone; my relatives in their 50’s have a hard time opening their messages and replying to the correct person. I am aware there are tech minded individuals in this age range but they are by and far the outliers.


Ultimately, these problems are going to get worse before they get better, with the exception of number three. Over time, nature catches up to everyone and kids are being exposed to computers at an earlier age and growing up with a computers all around them. So hopefully the next generation has an idea of what they are talking about and attempting to regulate. On the other hand, considering the wages top level Infosec Professionals, Developers and Software Engineers pull, it would indicate there is still a shortage of talent which likely isn't running for public office (*that's pays less*).


In closing,I urge you to think deliberate and  consider your leaders. I’ll leave you guys with this Mark Twain quote:

*“Whenever you find yourself on the side of the majority, it is time to pause and reflect”*

*Let me know if you liked this post and especially let me know if you hated it. Thanks for reading it.*

Josh Stepp
