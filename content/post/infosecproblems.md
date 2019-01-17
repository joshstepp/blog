+++
title = "How Infosec is Creating More Problems for Infosec"
description = "Infosec is hard to the general public, while this is good for salaries, it can be harmful to regulation and/or policy"
tags = [ "thoughts","infosec" ]
date = "2016-11-06"
categories = [
  "Thoughts",
  "Infosec"

]
slug = "infosecproblems"
+++
<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/titleinfosecproblem.png">


Information Security, cybersecurity or any flavor of security plus technology interest has skyrocketed and expected to grow exponentially. The reason is justified, criminals have moved into this section and been successful in exploiting victims for money then cycling those funds into developing more profitable ways to exploit targets. Furthermore, the domain of information technology provides a great return on their investment just by the scale at which these criminals can attack. Armed with email lists, password dumps and open source operating systems, attackers don’t need much more than a computer and an internet connection to start targeting thousands of potential victims. In the long term, this attacker would need to gather considerable technical skill along with adoption of operational security habits to prevent long prison sentences or being doxxed by <a href="https://krebsonsecurity.com/">Brian Krebs</a> , but the point is, the scale at which people can be targeted is large. Naturally, this leads to an increase in interest by the general public, especially those most likely to be compromised.

The issue with infosec is that it has received an exponential growth in interest from the general public while being perceived as some type of black magic only practiced by Russians and magicians in black hoodies on cable television. The general public has a general (at best) understanding of the basic principles of information technology, let alone the security practices involved with protecting data. At the same time, these individuals are a main driver of laws and regulations on information security implementation. This presents a problem, especially for security professionals who have legal jobs working with the same tools the bad guys use.

The public looks to the media to get their information and the main articles rotating social media are about the fringe ideas that get reported by two distinct, polar opposite groups. The first of which is the woefully ignorant, usually out to drive traffic to their site and I even hesitate to call them “Information Security Professionals”. In all seriousness, they shouldn’t be reporting on these topics without get consulting advice from real cyber security professionals.

The Grugq provides insight on discovering said cyber-security expert:

>If you want to hear a cyber security expert laugh, ask them how to avoid breaches from a determined well funded persistent attacker. If they don’t laugh, they’re probably not an expert. - the Gruqg

Okay getting back to our topic at hand. The second group of people are those individuals at the top of the information security food-chain who conduct research and uncover useful, meaningful advancement. However, they relay this information in a damaging way (or group one mis-interprets it) and due to their positional power within the information security field, it is taken as the second-coming of Jesus himself (Cyber Jesus), despite being a fringe case, not a plausible threat vector at the present time or only works in a lab environment. The items discovered by this bunch are usually going to target important heads of state, leaders of people/divisions in Fortune 500 companies, celebrities then normal, everyday people. Nation States and serious criminal syndicates aren’t going to burn their expensive 0-day exploit in the wild to get a few gmail accounts from bakers and soccer Moms. It’s just not a good return on investment. You wouldn’t throw fine China at an ant to kill it would you? It’s not worth it.

<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/cyberjesus.png">
To get a better understanding, I have linked two articles that represent the two groups discussed. Caveat: Article 2 isn’t the worse offender but it was recent so I posted it.

Group 1: <a href="http://www.gizmodo.co.uk/2017/02/the-uk-has-a-new-cyber-security-hq/">Woefully Ignorant</a>

This article started off with good intentions outlining the new GCHQ building as part of the UK’s cyber security initiative. At first, this article is decent, nothing  technical, just facts about the building and an unclassified mission state for the organization. Then the Author discovers a gaping hole in their security posture, their twitter feed isn’t hiding the gmail account that it is registered too. OMG, CALL THE CYBER POLICE! SOMEONE’S GONNA GET PHISHED AND PWNED!

<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/Internetpolice.png" />

Instead it has a partial address field with “uk” followed by 5 (*) and a gmail domain. Also she speculates that they aren’t using two factor authentication without any proof besides the previously mentioned insights. So just to prove how useful speculation is, I am going to assume that they have got two-factor authentication set.  I’m going to further break down why none of this matters and is a GREAT security principle other agencies/organizations should adopt.

Point 1: Using a gmail account instead of an official government e-mail server

GCHQ, unlike normal people, have more important things to secure than their twitter based gmail account. Additionally, they deal with classified networks and operate inside of a heavily classified building. Needless to say, the vetted, approved and sanitized tweets that occur on this medium are low on their list of critical duties. Furthermore, instead of storing this on official hardware, why not pass it off to one of, if not the most, secure e-mail hosting platform there is. Oh, and did I mention it is free?

There are numerous benefits to this:

1. It’s free, needed to state it again. Also to the government backdoor people preaching about this: They are the government and a member of five eyes.
2. It is most likely a segregated account just for social media/twitter. They aren’t receiving secure messages through this account. If they are, they have other problems.
3. It’s just Twitter. If it is compromised, someone could put out tweets that damage them in the court of public opinion on the short term, but doesn’t harm their national security.
4. It hides the official structure of their real e-mail naming convention. No mass phishing attempts on other employees.
5. It would take an insane amount of time/GPU farms to brute-force the meaning behind those 5 (*****) splats and fire off an exploit that gets through gmail. Furthermore, since gmail recognizes special characters for e-mail names there are roughly 7,737,809,375 possibilities. Good Luck.
6. You can have a non-cleared person running it from an unsecure location, like their home. Basically, it’s not annoying to keep track of and update the public. If Bob is in charge of the official twitter and he forgets to update it on Thursday like his boss told him too because he was reversing Stuxnet2 or resetting port security because someone plugged in their iPhone, he can do it at his house, from a tablet, while pooping. That’s real morale and job satisfaction.

At the end of the day, this article can paint the agency in a bad light over non-existent threats and can lead to lawmakers making regulations that could expose the agency to unnecessary risk. For example, mandating that all official social media accounts had to be tied to government e-mail servers. This could lead to the entire naming strategy of the government being discovered and thus opening up government employees to a barrage of malicious e-mails. It only takes one Podesta to ruin your career after all.

Group 2: <a href="https://arstechnica.com/information-technology/2017/01/antivirus-is-bad/?comments=1&post=32763781">Lonely at the Top</a>

The second article I wanted to highlight is more a trend from the security community about antivirus software and how it is not effective and may be opening up people to a larger threat area due to how invasive anti-virus is in order to protect against the vast array of malware it may encounter.  While factually true, this headline could be better worded in my opinion. Let's look at this from two perspectives. The first of which is from the normal user.

As a normal user of the internet, you will mostly likely be fine without a bought antivirus service. Save the money and get an extra latte once a month. Even with a purchased provider, you are still at risk for get compromised by opening something shady or going to a malicious website. My recommendations to limit this is outlined <a href="https://joshstepp.com/2016/12/21/ransomware-new-market/">here</a>.  With that being said, if you are running Windows, make sure your Windows Firewall is on and your Windows Defender is running. Couple this with Malwarebyte Free, automatic updates and good security practices (don’t click links in e-mail, don’t open attachments from e-mail and use 2FA)  this is enough to combat most, if not all the threats you will probably encounter.

Added measures I like to see is the use of Google Chrome to open all PDFs, Adblocker in the browser, macros disabled on Microsoft documents and the use of a password manager to prevent password reuse. If you check these boxes, you will be preventing a majority of standard, drive-by attacks that get most users.  

Ultimately, this article is true for most users. Get paid antivirus if it makes you sleep better at night, but it is not the silver bullet the vendors advertise. On the other hand, if you ARE in charge of protecting a larger organization with numerous users/customers/workstations. I would NOT ditch your antivirus yet. Call it career insurance.


Here’s why I am advocating most organizations still use antivirus in 2017:

1. When you are one in-charge of protecting many, you need all the help you can get. Antivirus is still useful against run-of-the-mill, old malware that is sent to users daily. If one of these get through your spam filter, you will be glad that your antivirus probably has had this signature for two years and can stop it from wreaking havoc on your Active Directory.
2. As a Security Professional, I would not want to be in charge of an organization that gets breached and in the first line of the report it reads “organization did not have an antivirus provider/service in use at the time of the breach”. Good luck getting through HR when they Google your name and previous job.
3. It is still somewhat useful in the attacks that cripple businesses daily, Ransomware. I am by no means an antivirus expert, however, in my experience, the antivirus I have seen deployed will alert the user that multiple files have changed in a short amount of time. This can help quarantine Ransomware attacks and prevent the burning of previously said active directory forest.
4. Compliance. In most fields like banking and medical records, antivirus is part of compliance that you must adhere to in order to operate.

As you can see, from an organizational stand-point antivirus still has it’s benefits. Furthermore, businesses dropping antivirus could be exposing their employees, customers, shareholders and intellectual property to unnecessary risk.

In conclusion Security Professionals should be outlining the risk of what they are reporting/documenting and who is most at risk. Sometimes you have to assume that the readers of your articles are 70 year olds who barely understand iOS, yet hold a seat on Congress. Otherwise, we will continue to see ineffective regulations like the purposed <a href="https://cyberlaw.stanford.edu/publications/changes-export-control-arrangement-apply-computer-exploits-and-more/">Wassenaar arrangement</a>  that hampers security researchers while not preventing what it aims to stop.

Thanks for reading and let me know what you think about this and leave me feedback at the social links on the side.

Josh Stepp
