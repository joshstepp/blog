+++
title = "Pelican to GOpher: Migrating my Blog to the Hugo Framework"
description = "A static site generator written in Golang"
tags = [ "thoughts", "blog" ]
date = "2017-08-29"
categories = [
  "Thoughts",
  "blog",
  "golang",
  "python",
]
slug = "migrateToHugo"
+++

If you have been to this site recently, you will have noticed that it doesn’t look the same. I have migrated from Pelican, a static site generator written in Python to Hugo, a static site generator written in Go (golang).

<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/gopher_Golang.png">

## Why?

My old blog just wasn't cutting it. The Pelican project updated and when I tried to migrate my local project from one computer to another with different versions I broke the site, which in turn went nuclear on my github repo for the project. I ended up fixing it, and getting the site back up, but this is just another example of my gripes with the python ecosystem.


## Python Ecosystem Gripes

I love Python, it was the first language I got to know well and it is fun to program in.... *most of the time*. Even doing the best practices of always using virtualenv environments and minimizing what is stored locally, I still run into hassles with dependencies, especially those libraries used in data science or data analytics. Nowadays, I usually just build  my more complex python projects in Docker containers and use virtualenv for the smaller stuff. It has worked out well, but despite Docker's small footprint, I feel like this process is heavy....heavier than it need to be.

## Back to Why

So why Hugo? Well, first of all Go (which I will be calling from know on) is awesome. It is crazy fast, has a great standard library and is compiled. Furthermore, you can build executables to run on anything.... oh and did I mention, it is fast. Second, the workflow and documentation is great. I spent more time customizing the CSS and Javascript than I spent figuring out how to deploy my page. 

## So How Easy is it to Migrate to Hugo?

If you can read the docs, you can deploy your blog. Seriously, that is all you need. If you can find another hosted blog on Github to see where certain directories and files go, it is even better. <a href="https://github.com/joshstepp/joshstepp.com">Here is mine!</a> ! All of these are covered in the docs, it is just easier to get it from a live site in my opinion. Lastly, the developers at Hugo give you a bash script that will deploy it when run once you add you commit message for git. Just make sure you follow the git sub-module process.  

## Closing up

In closing, if you are looking for a static site generator that is hassle free, doesn't demand engagement and can easily be host on Github, seriously consider Hugo. There is a reason Go has been exploding in popularity in the last few years.... It's awesome and Hugo is no different.

## Resources for Hugo
<a href="https://gohugo.io/documentation/">Hugo Docs</a> 

<a href="https://gohugo.io/">Hugo Main Site</a> 

<a href="https://themes.gohugo.io/">Themes</a> 

<a href="https://dave.cheney.net/resources-for-new-go-programmers">Go Resources</a> 