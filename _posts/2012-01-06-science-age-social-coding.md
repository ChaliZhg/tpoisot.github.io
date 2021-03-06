---
layout: post
title: Science in the age of social coding
summary: blog
type: essay
chapo: Code sharing has the potential of making our lives a little bit easier.
author: Tim
tags:
- github
- open source
- next-gen science
---

I started using version control a little more than 6 months ago, when working on my dissertation. Not only it allowed me to have a backup of my chapters somewhere else than on my hard drive, but I could also revert back to a previous version of some paragraphs I liked better. Sometime during the summer, I discovered GitHub, and thought that I can give it a try. A few months later, I'm wondering what I would do without it.

The idea of GitHub is simple: [*social coding*](http://radar.oreilly.com/2009/01/github-making-code-more-social.html). As in, everyone can work on your code, and contribute some new things to it. This blog is powered by Jekyll, many features of which originate from the community. In a way, social coding is open source logic pushed to its maximum: everyone can copy (fork) your code, work on it, and give you back the features they added, or the bugs they fixed, or whatever you can think of. Scientists would gain a lot by getting to know these tools.

# It will make us better coders

During the last few weeks, I've been taking a very informal programming course. And I've realized something: most of the code I write is horrible. It does the job, but it's not written the way it should be. I don't think it is a problem, given any code doing what I want it to do is good enough for me. But sometime, knowing how things actually work can make your program run faster, or do more advanced things. So there is a positive correlation between the time you will spend hacking around, and what you will be able to achieve. The only question is to maximize your benefit for every hour spent working on your programming skills. I found that social coding and version control helped me a great deal in this matter.

The first reason why is simple; it made me bolder. I used to write the basic layout of a program, then fix it by changing one line at a time. Now, I have the assurance that any revision of my code is available. Essentially, version control eliminated the question of "If I break it, will I be able to fix it back?". I can delete lines by the hundred, and rewrite them from the ground up, sometimes with a completely different logic. And I have the assurance that I can revert back to the previous version in case things go wrong. And much to my surprise, I've only rarely reverted back to previous versions. By taking advantage of the safety net that previous commits represent, it is possible to try new things, make drastic changes, with absolutely zero negative consequences (well, except for the time you will invest doing these changes).

In addition, GitHub has this bizarre effect of exposing any user to *a lot* of code, if you are curious and check out what other people are doing. There are a host of cool projects to explore, and when I see one with a specific feature, I can just check the source, and see how it's done. I prefer learning things by myself (I'm yet to buy a book about Python or R, despite the fact that I use both of them on a daily basis), but now I have the opportunity to see directly what more experienced coders are doing in the real world. This is not something to neglect, and I'm not only thinking about ecology-related projects. Just looking at the way people deal with different kind of data can give you ideas. GitHub is a great generator of serendipity, and serendipity is awesome because it brings you solutions to problems you didn't even knew you had!

# It will give us access to more techniques

One of the coolest things that can happen is that more and more scientists will use GitHub (or GoogleCode, or Bitbucket, which I use for stuff that I don't want you to see just yet) to post their code. I'm not saying it *will* happen, though [the young crowd is certainly doing it](http://innge.net/?q=node/19) – but I definitely think it *should* happen, and I play my part as an evangelist as often as I can. We are now sharing an increasing amount (and variety) of data (species distributions, functional traits, sequences, trophic interactions, and what not), but strangely, there is no global code repository that I know of. Let me put it another way: finding the raw material is becoming less and less of an issue, yet very few people seem to be actively thinking about how to share the *tools to analyze these data*. This is too bad, for a whole lot of reasons.

First, it's time consuming to re-write an algorithm from the ground up, simply because the original code was not shared. Describing a kick-ass analysis is not really useful if nobody can do it. It's not useful for your community, which will be unable to do what you propose. Even though some people will *want* to do the analysis, they might be unable to do it because they don't know any programming or scripting language, or have no resident geek in their lab who can write it up for them. And more importantly, an analysis that no one can replicate is not useful for you, because no one will cite your paper.

Second, we are subjected to the limitations of existing software. I've been discussing this matter with non computer-minded people working on pyrosequencing. The discussion went something like "Hey, it would be super cool if you were able to do \[so and so\] !". To which they replied "Yeah, but we can't, because it's not in \[whatever program we are using\]". Should the code be public, it would be a simple matter of forking it, and adding this new functionality. Given the way GitHub works, this modification could even one day make it into the main release, which will bring you some kudos among your peers for making everyone's life a little easier.

And finally, there is one additional impact of an increased availability of the code: people will develop more integrated tools. Part of my motivation for writing [bipy](http://tpoisot.github.co/bipy/) was to have an integrated way to work with bipartite ecological networks, to do a bunch of different analysis in a common environment. The folks at [ROpenSci](http://ropensci.org/) are doing an impressive job of stitching together a lot of different databases, and their project is a prime example of what we can do with open source. Similarly, [Weecology](http://weecology.org/resources) is publishing both code and data. By merging these tools together, it's increasingly likely that people will stumble across new analyses, think "Hey, that's cool, I'd like to do it", and increase the diversity of methods in different fields.

# Where to start ?

As Nick Barne put it, [*publish your code, it's good enough*](http://www.nature.com/news/2010/101013/full/467753a.html). Open an account somewhere, and try pushing a random file around. GitHub makes everything public by default, unless you pay, but [BitBucket](https://bitbucket.org/) will allow you up to 5 privates repositories (I you want version control for something you are currently working on, and although you may not now it yet, you do want it — a lot). Then spread the world. Give the URL to your repository in the methods or acknowledgements of your papers, put the URL in slides at conferences, and so on.
