+++
title = "Home Lab Part I : Approaches and Why"
description = "Why You Need a Home Lab and How to Get Started"
tags = [ "thoughts", "infosec" ]
date = "2017-11-29"
categories = [
  "Thoughts",
  "blog",
  "infosec",
  "Active Directory", 
  "books",
]
slug = "homelabpt1"
+++


This will be a multiple part post outlining my opinions of homelabs and what you should consider when building your lab. I will also include a few resources I can vouch for and have used. Furthermore, I do not claim to have all the answers and your setup/needs will be different from mine. That being said, I will start off in a general sense and narrow done as these posts go on. 

## First, Do I Need a HomeLab?

If you are in IT, Information Security, Penetration Testing, DFIR, Reverse Engineering or any flavor of those disciplines, the answer is Yes. The last thing an organization wants is to rebuild their Active Directory environment or be taken offline because you want to work on your “dank” powershell scripts. And for the penetration testers out there, this isn’t North Korea <a href="https://www.wired.com/story/north-korea-cyberattacks/">you can't be Cyber Vikings here</a>. Additionally, having the ability to get hands on experience is priceless in tech professions.

## Hardware

The most intimidating part of this process is picking the best equipment and getting your money’s worth. The good side is that for your first lab, here in 2017, just about anything you get will be able to get you started. As you get more experience, you will need to expand, but by that time, you will have a better understanding of the hardware and resources you need. Overall, think lean. Start cheap and outgrow before upgrading. 

## First Option: The Cloud!

For those with very little space, the cloud could be a good option but it comes with a lot of tradeoffs. It’s no secret that everything is moving to this mythical land of servers called “the cloud”, so getting hands on experience in that environment can be beneficial. However, the cloud can be more hassle than it's worth. 

First, you need to read the terms and conditions carefully because although you do own the VM’s, service providers usually don’t want you testing against their infrastructure. Additionally, some cloud providers only provide *nix environments, so getting a Windows domain will not be possible. Lastly, the cloud provided VMs can be difficult to manage or even impossible to set up for more obscure environments. 

Generally, I would advise against this. Although the upfront cost is low, the cost over time will quickly catch up with you. 

## Second Option: Use What You Got!

Chances are the laptop or desktop computer you have now can get you started. For the most part, VMs love memory, CPU cores/threads and solid state drives, all of which are becoming more common in consumer-grade equipment. Additionally, this can be the least expensive option if you already have a useable one.
Things to consider:

1. The CPU has to support hardware virtualization, which usually needs to enabled in the BIOS. You are looking for Intel VT or something along those lines.
AMD, Pentium, Atom and Celeron processors usually don’t support virtualization. You really want to look for a Core i3, i5 or i7. 

2. More Memory = More VMs. For a laptop, I would not go below 16GBs ( before you throw away your current laptop, do a google search and see what the max RAM your current model can take. As long as it is not soldered to the motherboard, upgrading RAM can be done pretty painless with hand-tools) For a desktop, I would aim for 32GB personally, but like the laptop, 16GB will get you started. 

    *For a Windows Server and Client I use 2GB or 3GB depending upon the other boxes I have running. These will be slow but remember, you are not maintaining uptime for a Fortune 500 Company. This is a cheap lab used to learn with, you can live with a little bit of slowness.*

3. The Solid State Hard drive is a nice to have, but not required. Personally, I use a 500GB Samsung EVO in all my equipment but for just a lab you could be perfectly fine with older spinning drives. 

If you are buying for this route, I would suggest older Thinkpad Laptops with either a Core i5 or i7. For desktops, I love Optiplex i7 mini-towers (These can fit GPUs as well with a PSU upgrade and usually come with Windows Pro COAs)  but the dual Xeon T3500, T5500 or T7500s on ebay can be a great option as well. 

This option is great if you have existing hardware, but it might not support enough VM’s for your use case and can be the least functional. 

### RESOURCES: 

<a href="https://www.psattack.com/articles/20160718/setting-up-an-active-directory-lab-part-1/">psattack homelab </a> series

<a href="https://cyberwardog.blogspot.com/2017/02/setting-up-pentesting-i-mean-threat.html"> CyberWarDog's Threat Hunting Lab </a> series

## Last Option: Dedicated Servers/ Hardware

This option is by far the most flexible, ranging from a desktop running ESXi to server racks with dedicated cooling. For a beginner, I always advise to go slow and outgrow your lab before going all out, especially if you are married, in a one-bedroom cramped apartment. Personally, I went with a dedicated rack server (Dell R710) as my first server and it was too much for my uses. The noise from it, despite being a quieter server annoyed me and I just wasn’t using it to it’s full potential. I sold it and downgraded, and decided to write this post to help others not make the same mistake.  

If you are going this route, my opinion is to look for a Dell r710. These are plenty powerful, have a huge following (looking up solutions will be easy for any problems you encounter), and are a bargain these days. 

### RESOURCES

<a href="https://www.reddit.com/r/homelab/">r/homelab </a> 

<a href="http://amzn.to/2BE53hK">Building virtual Machine Labs: A Hands-on Guide</a> by Tony Robinson

## Conclusion 

In closing, a home lab provides you an environment to get your hands dirty and really know a stack, framework, etc. However, building one doesn’t have to break the bank, and chances are you already have something suitable to get started on. In Part II of this series I will discuss my frankenstein setup and Part III I will outline some uses, tutorials or guides on cool things you can do in your lab. If there is more you would like to see, let me know!
