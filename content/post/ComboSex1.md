+++
title = "ComboSex.py: A Simple Python Tool to Spark Creativity / Part 1"
description = "Based on a James Altucher blog post, I created a tool that combines 2 words from a scraped data set"
tags = [ "creative","python", "project" ]
date = "2017-06-02"
categories = [
  "python",
  "creative",
  "project"
]
slug = "combosexPart1"
+++


<img class="pure-img" img style= "display:block; margin-left: auto; margin-right: auto;" src="/img/post/combosex1.png" />

ComboSex.py is a simple Python Tool that uses a scraped word list to combine random word combinations in an effort to spark creativity. The tool was inspired by a blog post from James Altucher called <a href="http://www.jamesaltucher.com/2015/10/how-to-make-millions-with-idea-sex/">"How to Make Millions with Idea Sex"</a>. The principle is simple, combine two seemingly non-related objects to get the new hotness.

Dolls + Action = G.I. Joe

Space + Buddhism = Star Wars

Plus, millions of other examples you could come up with. The point is to get the juices flowing.

### Nitty-Gritty

Since this tool is still an infant, it has some issues I will be working out in the next coming days. Essentially, the tool is a while loop that gives a pre-determined number of results (default 10) of two word combinations. The database is a text file with all the results combined together, one word per line.

### Gotcha's that Need Work

1. The word list needs work. I need to parse the one character words out and I would like to add more than just nouns, verbs, adverbs and adjectives. Movies titles will be my next addition to the word list barring some crazy copyrights I am currently unaware of.
2. More Variety. As it sits right now you can manually go into the script and change the while loop to produce more than 10 results of two word combinations I would like to give the user more input on the front end. This is easy, all it takes is establishing variables. I wanted to think about other possibilities and do it all at once.
3. Make it pretty. I have been wanting to use Kivy for a while but didn’t have a good reason to dive in and mess with it. This isn't the best script for it, however, this should be able to give me worth while practice with the library.
4. Export the Results. I haven't come across this yet, however, it's an easy feature and would like the possibility of exporting the results, probably in CSV format.

The source files can be seen on <a href="https://github.com/joshstepp/combosex.py">Github<a>.

Josh Stepp
