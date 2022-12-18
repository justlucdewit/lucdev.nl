+++
title = "Thoughts on ‘Github Copilot’ after 4 months"
date = 2022-08-16

[taxonomies]
tags = ["AI", "tools", "opinion"]
+++

## I Tried Github Copilot for 4 months, here are my thoughts, tips, and tricks.

<br />

### Github Copilot
Earlier in 2019, Github revealed its latest project: Github Copilot, an AI-based on OpenAPI GPT-3, and I was among the people to try it out for free. This article is about my thoughts on the experience, and some tips/tricks I discovered while using it.

<br />

### Beta access
Before Github Copilot was available for the general public, Github decided to make a beta testing program where people could join a queue to try it out until it was released. I was one of the lucky people that gained access to this program and as soon as I set it up, I was hooked.

<br />

### Initial impressions
Once I saw that I was accepted to the beta testing program, I quickly set it up on visual studio code and started making a small 1-day project to see how it affected my workflow, and I quite quickly found out that this has the capabilities to revolutionize the way and speed at which I code.

<br />

### First project
I decided to do a quick 1-day project to see how Github Copilot will affect my workflow. My idea was to make a personal finance API that could track and summarize transactions over multiple banking accounts.

I decided to do this in express.js, a NodeJS framework for backend servers and APIs. As soon as I started with the standard technique of writing comments and letting Copilot do its job, I could generate the endpoints very fast and without that much trouble.

The only issue I sometimes experienced was Github Copilot getting into an infinite loop of repeating itself, and generating longer and longer lines of code

![repeating issue](https://miro.medium.com/max/720/0*rEpsAg7UUOgqkPYu)

There wasn't any way for me to fix this except for writing some of the code myself or formulating the comment in another way, Which was annoying.

These days Github copilot does seem to perform much better though, and I get issues like this way less often.

<br />

### Other use cases
Another way to use Github, which I often do, is to do the process in reverse, instead of writing comments and letting Github copilot figure out the code, you could write the code and let Copilot figure out the comments.

That way you could easily develop the habit of properly documenting your code, without having to think about what to write.

Often, however, I use a mix of both writing the code, and writing the comments. I find this to work the nicest for me, but it's important everyone figures that out for themselves.

<br />

### Downsides
Using Github Copilot also comes with its downsides, I would not use it if I was super scared of accidentally having code of someone else in my codebase (tho it is trained on open-source code, so that shouldn't matter).

Also, Github Copilot can work very terribly on non-mainstream programming languages. I had to disable copilot for AL and C/AL because it kept generating syntactically flawed code, even tho the context had plenty of examples of how the AL syntax worked.

<br />

### Conclusion
Github Copilot can be a helpful tool in your development process and ca revolutionize the way you code. However, it is still important to keep in mind the diverse ways of making use of Copilot, and trying to figure out whatever workflow works for you.