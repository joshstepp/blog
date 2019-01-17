+++
title = "Reverse Engineering Resources for 2019"
description = "Some RE resources for beginners"
tags = [ "reverse engineering","infosec", "training" ]
date = "2019-01-01"
categories = [
  "Training",
  "Reverse Engineering",
  "Infosec"
]
slug = "2019REresources"
+++

As the New Year has arrived, I wanted to take this time, not to outline my resolutions or goals, but to write the post I wish I had when I got into reverse engineering/ malware analysis. Beware, there are numerous more resources than what is listed here, these are just resources I like and recommend. 

## Books

<a href="https://amzn.to/2GS5FXM">Practical Malware Analysis</a> by Andrew Honig and Michael Sikorski

This was my first book on the subject and is a great primer to understanding malware characteristics. 

<a href="https://amzn.to/2StqoCA">Practical Reverse Engineering: X86, X64, Arm, Windows Kernel, Reversing Tools, and Obfuscation</a> by Bruce Dang

More of a reference book and I have learned alot from this book, but it can be difficult to read.

<a href="https://amzn.to/2s64zgL">Reversing: Secrets of Reverse Engineering</a> by Eldad Eilam 

This book was enjoyable to read and really covers the basics well.

<a href="https://beginners.re/">Reverse Engineering for Beginners</a> by Dennis Yurichev

It's free and packed full of knowledge. 

## Tutorials

<a href="https://sites.google.com/secured.org/malwareunicorn/reverse-engineering/re101">Malware Unicorn's RE101 </a>  course is amazing and introduces you to the tools of the trade quickly. Her entire website is a wealth of information and look up her talks on youtube as well!

<a href="https://securedorg.github.io/RE102/">Malware Unicorn's RE102 </a> is just as good as the first and really ramps up into some interesting malware tactics. 

 
<a href="http://opensecuritytraining.info/">OpenSecurityTraining.info </a> 
 is like the Khan Academy of Computer Science/ Security. 


<a href="https://tuts4you.com/e107_plugins/download/download.php?action=list&id=17"> Lenas Reversing for Newbies </a>  is a great introduction to RE.


<a href="http://flare-on.com/"> Flare-On by Fireeye</a> is a CTF they host every year and has write-ups to every solution along with the binary. Plus they provide the flare-vm as well. Amazing training!

<a href="https://azeria-labs.com/writing-arm-assembly-part-1/"> Azeria Arm Labs</a> are ARM based RE exercises. ARM is a totally new beast to me and I haven't went through all of these, but it is great from what I have seen.

## Virtual Machines

<a href="https://github.com/fireeye/flare-vm"> Flare-vm</a> requires a Windows VM to install on top of but this suite will give you every tool you could need to work with Windows-based malware. 

<a href="https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/"> Windows Trial VMs</a> are here. Pick your VM software and snapshot it after import, but before powering on. Then Snapshot it again once all the tools are on. Go to the original when your trial is over and can not be renewed.

<a href="https://oalabs.openanalysis.net/2018/07/16/oalabs_malware_analysis_virtual_machine/"> OA Labs VM</a> is similar to Flare but has less tools and is built for their youtube tutorials. They recommended a Win7 32 bit I believe. 

<a href="https://remnux.org/"> Remnux </a> is an Ubuntu-based toolkit for reverse-engineering. Almost all the tools are command-line based and can handle most jobs. Additionally, the documentation is great and provides starting points for what tools to use and when. And it's free!


## Samples

<a href="https://cape.contextis.com/analysis/search/"> CAPE Sandbox</a> is a open sandbox that allows you to download what is submitted. 

<a href="https://github.com/ytisf/theZoo"> The Zoo</a> is a github repo of some popular malware and good stuff to get your feet wet with. Most of the PEs here have write-ups, so you can check your work.

<a href="https://malpedia.caad.fkie.fraunhofer.de/"> Malpedia</a> houses samples, report links, and yara rules for a ton of malware. My favorite, but you do need to be vetted before joining this site.

<a href="iec56w4ibovnb4wc.onion"> 0xffff0800 Library</a> is a TOR hosted site (you can just add .to to the end of the URL) with a ton of great samples, mostly from APTs. True hero for hosting this!

## Youtube Channels

<a href="https://www.youtube.com/channel/UC--DwaiMV-jtO-6EvmKOnqg"> OA-Labs</a> has great tutorials and knowledge packed videos. Speaking about packers, if you are dealing with one, these guys probably have a video on how to get around it. 


<a href="https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A"> Malware Analysis For Hedgehogs</a>  is a another great resource, especially the PE videos.


<a href="https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w"> Live Overflow</a> does a great job explaining concepts and showing how to apply those concepts to reversing.

Happy Reversing!

Josh Stepp
