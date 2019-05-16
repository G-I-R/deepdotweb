---
layout: single
title: "Deep Dot Web -UNOFFICIAL- Blog Archive and Privacy Guides"
description: "The world needs user-friendly access to the educational materials that were previously available on deepdotweb.com."
header:
  image: "/free_ross.jpg"
  caption: "[freeross.org](https://freeross.org/)"
classes: wide
toc: true
permalink: /
share: true
sidebar:
  - title: "Security Tutorials"
    nav: "security"
  - title: "Jolly Rogers Security Guide"
    nav: "jolly"
  - title: "Blog Archive"
    nav: "blognav"
---


**Archive: Privacy Guides, and History from DeepDotWeb.**


I was broken-hearted when I found out that deepdotweb got seized.

The world should have user-friendly access to the educational materials that were previously available on deepdotweb.com.

I have never bought anything from the darkweb, and have no particular inclination to use or facilitate use of the markets.

However, its clear that governments use the drug war to suppress their populous and take massive profit on both sides.

I certainly don't have any problem with the use of the markets, in fact I think they are great, when successful. I simply don't have any personal use for them, and am not trying to get caught up in all of that.

![](https://imgur.com/T7QpFTM.png)

## Why Did I Build This Archive?

Of course you can still visit [DeepDotWeb at the Internet Archive](https://web.archive.org/web/20190228074725/https://www.deepdotweb.com/), which begs the question: Why did I build this archive?

A few reasons.

1. Preserve content essential to humanity.
2. Practice building static websites.
3. Study Bitcoin History.
4. Show off the content of DeepDotWeb to Highlight some of it's most important contributions.

Though I'm grateful for the internet archive, I thought I could do something nice with [Jekyll and Github Pages](https://infominer.id/web-work/github-pages-starter-pack/). 

* [WiReD: FEDS DISMANTLED THE DARK-WEB DRUG TRADE—BUT IT'S ALREADY REBUILDING](https://www.wired.com/story/dark-web-drug-takedowns-deepdotweb-rebound/)
* [DeepDotWeb Dark web resource dies with FBI seizure](https://www.zdnet.com/article/deepdotweb-dies-with-fbi-seizure/)

![](https://g-i-r.github.io/deepdotweb/deepdotweb-seized.png)

## How I Created this Archive

[Download a Website from the Archive.org Wayback Machine](https://superuser.com/questions/828907/how-to-download-a-website-from-the-archive-org-wayback-machine)

    gem install wayback_machine_downloader

and then:

    wayback_machine_downloader https://deepdotweb.com

## Snip and Clip

I'm stripping away all the header material and the comments so I can spin up a simple site, without having to host everything, and really trying to get it done asap because I have other stuff I should be doing.. 

* [https://github.com/Ruined1/HTMLArticleElementStripper](https://github.com/Ruined1/HTMLArticleElementStripper)

This app goes through and strips away everything besides what's between `<article>...</article>`.


From there, I used VSCode to prepare the content.

First of all, I deleted all amp pages, feed pages, comment files, memes.. whatever I could strip away quickly to be able to work with the essence.

I used VSCode which has a really nice search and replace funtion that works with all files in the directories it has open. But it was crashing a lot, trying to edit so many files at once.... so I deleted more and more, and edited less at a time.

I also learned to use RegEx to put wildcards in my search query to make it even more powerful, and speed up the process.

* [Using Regular Expression in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/using-regular-expressions-in-visual-studio)


I also removed the market directory and forum. For space, and really it's not my interest to connect people with darknet markets. I firmly believe, however, that anyone who desires should have free access to information on how to protect your privacy online, and the history available in the blog-feed.

* [Rename Files with Path Name](https://unix.stackexchange.com/questions/137419/renaming-files-with-its-path-name)

There was also the matter of restructuring the format of the post title\directories to match that of Jekyll.

Currently this site is being published with the [Minimal Mistakes Theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

Mostly because it's the one I'm most familiar with at the moment. 

However, once everything it set up, changing themes can be relatively trival.

## Internet Archive Asked to take down "Terrorist Content"

* [Archive.org hit with hundreds of false terrorist content notices from EU](https://www.google.com/amp/s/www.theverge.com/platform/amp/2019/4/11/18305968/eu-internet-terrorist-content-takedown-mistakes-internet-archive-org)

This was another reason I was concerned that I shouldn't leave it up to the Internet Archive to protect our ability to learn best practicees for privacy online.


![](https://G-I-R.github.io/deepdotweb/free_ross.jpg)