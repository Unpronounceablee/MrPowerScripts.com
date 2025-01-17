---
layout: post
title: How to use git version control
date: 2018-10-24 13:00:45+00
categories: [git, tutorial]
tags: [mrpowerscripts, git, how do I use git, how do I use version control, git version control, development version control]
description-long: When I first started scripting my development flow when something like this Create a script and save it as a file. Make some adjustments I want to test and save it in a new file. Make more adjustments and save it as a new file. Rinse, repeat. I would end up with a folder full of different file versions with different names that all were effectively the same script. If you're doing things this way then STOP. Watch the video above and save yourself. After learning to use git I was vastly more effective in terms of speed and organization of my code.
---

When I first started scripting, my development flow went something like this: Create a script and save it as a file. Make some adjustments I want to test and save it in a new file. Make more adjustments and save it as a new file. Rinse, repeat. I would end up with a folder full of different file versions with different names that all were effectively the same script. {% include youtubePlayer.html id="NwQ0M-pyeHQ" %} If you're doing things this way then STOP. Watch the video above and save yourself. After learning to use git I was vastly more effective in terms of speed and organization of my code.

I first encountered git when I join a remote development team. Many people were working on the same code base and my existing practices definitely weren't viable. They taught me how to use git in my first few weeks. It was a huge challenge. There are so many commands and weird words I'd never used in the process of developing. What is a branch? What the heck does master mean? What's the point of a SHA? It all seemed really daunting for me.

I realized after some time that git is one of those tools where 99% of the time you'll use 1% of the features it offers. Even that small portion is enough to completely revamp the way you manage your code. Once you have the basics down you can really appreciate some of the more advanced toolings that are available.

`git bisect` is a great example of this. By breaking all of your code changes into individual orderly commits it helps maintain a clear stream of changes to your code. If many people are working on the same codebase and making lots of changes it can be difficult to figure out when a change was introduced that broke something. `git bisect` is a command that helps you traverse all of the changes to the code very efficiently to identify the precise commit that introduced the change. Even if you're not familiar with the code or someone else introduced the breaking change.

Modern development is possible because of version control systems, and I think git is a really great place to start for anyone who wants to become a modern developer.
