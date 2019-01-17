+++
title = "Home Lab Part II : My Setup"
description = "A breakdown of my work horse and why it is built this way"
tags = [ "thoughts", "infosec" ]
date = "2017-12-28"
categories = [
  "Thoughts",
  "blog",
  "infosec",
  "Active Directory", 
  
]
slug = "homelabpt2"
+++

My Homelab is a work horse for me; I use it to train smaller machine learning (tensorflow) models on, mess around with <a href="http://www.starcraftai.com/wiki/Main_Page/">Starcraft AI bots</a> on it, along with doing Information Security research and some light malware analysis/ reverse engineering. Essentially, it is a jack-of-all trades, master of none type of workstation. 

**Going in I had the following requirements:**

* CHEAP… I want this to be under $300USD (not counting the GPU)

* Able to support a GTX1070 GPU

* Able to make use of three drives and a CD/DVD Drive

* Support VirtualBox with 5 Virtual Machines going at one time 

* Dual Boot Windows and Ubuntu  

*Prerequisites - Items I Already Had*

I had a 500 GB SSD and a 500 GB HDD, so I only purchased one additional    250 GB SSD


Peripherals - Keyboard / Mouse and Monitor 


## The Setup 

**Optiplex 3020 MT Core i5-4590 3.30Ghz - 135.00 + 21.00 USD Shipping (156.00 Total)**

I LOVE older Optiplexi (?). You can get a lot of performance for next to nothing by re-purposing these machines after they leave their dreaded life in the corporate world. Seriously, I have gotten so many of these machines just off the curb or on their way to the garbage can. The Small form factor (SFF) models are great if you just need a system to do normal computer work on (browse the internet, e-mail, Microsoft Office work, light gaming) but the real value is in the mini-towers. Gamers have been snatching these up for years and throwing a low-power GPU in them and having a budget gaming system that can handle most modern games on lower settings. Furthermore, since they run some flavor of Core iX series chips, they support any virtualization needs you may have (enabled from BIOS) and for a pure home virtual lab server, I have even hosted ESXi off a USB drive on one of these. 

For my build, I went with the minitower as well because it can hold a Single GTX1070 and accepts an ATX sized PSU, albeit the cable management requires some creativity. Lastly, the case also met my needs for drive capacity. If I had more time to look, I would look for an i7 option on craigslist or local government auction before ebay. YMMV.

**EVGA 220-B3-0750-V1 750W Bronze PSU - 96.00 USD Shipped**

I needed this for the machine learning aspect of my homelab, for a normal Infosec/sysadmin lab this item can be skipped. 

**16 GB DDR3 1600 RAM / G.Skill RipJaws - 100.00 USD Shipped**

Nothing really special here, I just bought 16GB of RAM that seemed affordable and didn’t look like it was made in someone's basement. I just needed enough to run my Virtual Machines.

**My Active Directory Lab Setup**

* Windows Server 2016 : 30 GB // 3 GB RAM

* Windows 10 Pro : 20 GB // 2 GB RAM (x2)

* PFSense : 10 GB // 1 GB RAM 

**Other Systems that get switched on and off depending upon what I am doing**

* Kali : 35 GB // 4 GB RAM 
* SIFT: 30 GB // 4 GB RAM
* Ubuntu Web Server (Hackazon):  15GB //1 GB RAM
* ElasticStack Ubuntu Box: 40GB // 4 GB RAM 
* Security Onion (Elastic Install): 50 GB // 4 GB RAM

## Bare-Bones Lab Box 

If I was doing this for pure information security research, I would get the best optiplex minitower I could afford, stuff it with 16GB of RAM, get a 500GB SSD and run Ubuntu on it with virtualbox hosting my lab environment. All this could be done for less $400USD and would take a while to out grow.  *Bonus points if the Optiplex has a Windows COA on it.*


### EDIT: Jan 2018
Another option, although a little more expensive but more solutions to expand would be getting a Dell T7500 with as many CPUs and as much RAM as you can afford. These come with huge PSUs and if you want a Machine Learning Rig as well, they support large GPUs. Furthermore, for the lab, they can run on some versions of ESXi, so I am told. 

### /EDIT: Jan 2018


LPT: Windows Server 2016 can be downloaded for free in an educational setting using the Microsoft Imagine portal as long as you are a student.  Otherwise, you can download trial versions as you see fit. I do this sometimes to see new builds and baseline them with my tools so I am not chasing a PE file I haven't seen before on newer systems. 


##  Conclusion

My setup is tailored to my needs and interests. I am fascinated by many subjects and just needed a workhorse system that wouldn’t break the bank. Remember this! It is a home lab, not a production environment, so give the virtual machines enough resources to function correctly, but don’t get get bent out of shape by using less than minimum specs. No end-users will be calling you about latency. Additionally, there is no need to go overboard right off the bat. Large rack mounted servers are cool, but they also eat a lot of power, make a ton of noise, and you need somewhere to put it. Grow into that! Lastly, this little setup has gotten me far, I mean I am no <a href="https://infosec.engineering/"> Jerry Bell </a> of course, but I am getting there!


Hopefully, this helps you in deciding your setup and feel free to contact me via the links on the side or by opening a ticket.

Part I:  <a href="https://joshstepp.com/post/homelabpt1/">Home Lab Approaches and Why</a>







