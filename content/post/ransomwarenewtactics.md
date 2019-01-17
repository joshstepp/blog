
+++
title = "Ransomware: The New Massively Disruptive Market?"
description = "Popcorn Time ransomware employs multi-level marketing from the business world to creatively deploy ransomware to more users. "
tags = [ "thoughts","infosec", "cybersecurity", "ransomware" ]
date = "2016-12-21"
categories = [
  "Thoughts",
  "CyberSecurity",
  "Infosec"
]
slug = "ransomware-new-market"
+++

Ransomware, malicious software designed to encrypt a victim’s hard drive and charge a ransom for the recovered files, has been reigning terror or organizations and users for a number of years now. The business model has always been simple, infect the user through spam e-mail or other vectors of infection (i.e. online droppers), encrypt the hard drive and hold it hostage until the user pays the ransom in Bitcoin. Rinse and repeat. This has been successful for attackers because it requires low technical skill to deploy (compared to finding 0-day) while casting a large net (especially if you consider the large number of breaches in 2016 and the massive e-mail lists from them).

Enter Popcorn Time, this new flavor of ransomware uses the same tactics of encrypting key files then charging for the recover of said files. What makes it different is that victims can share the love and send the ransomware to other people and once they are infected and pay, the original victim gets their decryption key (and two less holiday gifts). Additionally, Popcorn Time ties into human sympathy and tells the infected users that they are Syrian computer science students and need this money for aid. Clever tactic to possibly entice a few more ransom pay-outs, but I assume the real beneficiaries are somewhere in Eastern Europe or Russia.

### How to Protect Yourself

To start off, I believe the likely hood of you getting this ransomware in the wild is extremely low. It has had the benefit of being different and scary on the surface. General malware/ransomware prevention should be enough to combat Popcorn Time. Next, at the time of this writing, Popcorn Time has not been seen in spam e-mail, so it would need to trick the victim into downloading it.
Let’s dive in.

The initial response of spinning up two VMs (virtual machines), sending the ransomware to those machines, deploying it, then nuking the box to get the keys will not work, the other users need to pay. So doing it this way would really cost you double.

Now before you delete VMWare or VirtualBox from your computer, instead spin up a virtual machine, or three to segment your network (really your system). Businesses do this all the time to keep the sales teams separate from the production teams and so on. Depending on what services and software you need, it’s entirely possible to use one virtual machine for the “risky” internet browsing, checking of e-mail/ opening attachments and one to do work in offline (could even be your host).  If your browsing/e-mail box becomes infected, just go back to previous known good “snapshot” or version.

One setback to this approach of segmentation is licensing for the Operating System and software needed to conduct business.  For most users, <a href="https://www.ubuntu.com/download">Linux Ubuntu</a> (free) is simple to learn in a few minutes and more than capable of running Firefox and Chromium (Google Chrome). Additionally, word docs and other Microsoft documents can be opened using open source Linux programs (Libre Office) already installed at startup. Remember, this is only for browsing the internet, checking e-mail and opening attachments.  No need to mess around in the terminal, although those skills are nice to have (but that’s a different post).

Like all aspects of life, this approach does not totally mitigate all risk associated with the internet and malware/ransomware. The developers of these programs are in a constant arms race to get around virtual machines, Malware Hunters, Anti-virus and overall detection. If possible, run the browsing VM with more than one processor because some malware can detect that it is in a VM and won’t deploy, thus sending out a false sense of security.
In conclusion, Popcorn Malware is not the Uber of the ransomware world but, it does signal the creativity of developers that are adopting marketing and sales tactics for a better conversion rate. Using a virtual machine can limit the risk of exposure to this ransomware and others but it is hardly a “silver-bullet”. Ultimately, users need to treat all attachments as hostile and vet download requests they do receive.



Happy Holidays, and remember this is the season of giving, but not ransomware…

Josh Stepp
