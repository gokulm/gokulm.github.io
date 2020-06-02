---
layout: post
title: Markdown based blog
description: Markdown based blog using Jekyll and GitHub Pages
tags: [markdown, jekyll]
---

After getting fond of [Markdown](https://en.wikipedia.org/wiki/Markdown#:~:text=Markdown%20is%20a%20lightweight%20markup,same%20name%20only%20supports%20HTML.) while documenting my open source project [BoltOn](https://github.com/gokulm/BoltOn), decided to use a blogging engine based on Markdown.

Did a basic research, and found out that [GitHub Pages](https://pages.github.com/) with [Jekyll](https://jekyllrb.com/) to be the simplest one in terms of setup and maintenance. 

Instead of installing Ruby and other things, used Docker to set it up by following [this article](https://medium.com/@sebagomez/setting-up-a-github-page-with-jekyll-and-a-docker-container-c712e448649b). 

Here is the command:

    docker run -v /Users/gokul/gokulm.github.io:/srv/jekyll -p 4000:4000 -it jekyll/jekyll:builder bash

Here is the [theme](https://jamstackthemes.dev/theme/sidey-jekyll/) I used.