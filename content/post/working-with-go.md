---
title: "Working With Go"
date: 2023-05-26T22:41:19-05:00
draft: false
author: "Vincenzo Fehring"
categories: ["devlog"]
tags: ["languages", "go", "discord"]
---

After some small adventures with the Nim programming language, I decided it was time to test Go for the first time. After a few quick
"hello world" tutorials, and adding some basic features, I decided to make the jump to a "real" project. I started converting one of my
long running Python projects into Go. This was an interesting experience, as the primary Go package for interacting with the Discord API,
is more of a low level abstraction, instead of a framework for building your bot on top of, unlike the Discord.py package.

After ruffling around in VSCode for a bit, I was able to not only get everything setup, but I was able to add some basic functionality to
the bot that will be beneficial in the long run, such as a database connection. After a few short hours of messing with Go, I felt that I
had a pretty good grasp on it, since I know how to program in C. The speed at which I was able to start adding some basic features, and get
a compiled binary that I could launch and test was significantly faster than I have experienced with Python.

So, all in all, my first real interaction with Go could be categorized as a success. I will definitely expand more on this, as I feel that
tracking this adventure, can definitely prove to be useful. If not for me, but hopefully for someone else.