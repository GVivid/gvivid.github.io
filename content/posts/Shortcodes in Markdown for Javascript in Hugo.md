---
date: 2025-07-12T18:53:57+03:00
draft: "false"
title: Shortcodes in Markdown for Javascript in Hugo
---
I wanted to know how to host Javascript applications on this website. After some research, I discovered that you can use [shortcodes in markdown files](https://discourse.gohugo.io/t/javascript-in-blogpost-but-not-on-all-sites-at-the-same-time/3978/14) when generating a hugo website. So, you can place your javascript files into the shortcodes folder in your hugo directory, and then use the shortcode syntax right within your markdown file. This might be helpful for creating a portfolio of Javascript applications.

{{<js-calculator>}}

Calculator from here: https://www.geeksforgeeks.org/javascript/javascript-calculator/