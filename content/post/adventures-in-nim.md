---
title: "Adventures in Nim"
date: 2023-05-17T01:38:14-05:00
author: "Vincenzo Fehring"
draft: false
categories: ["devlog"]
tags: ["languages", "nim", "discord"]
---

After being introduced to the Nim programming language, I decided to give it a whirl for a little while. Seemed close
enough to my current favorite language, Python. I decided that for my first go with the Nim language, I would work on
converting over a Discord bot that I had written in Python. After about 10 minutes, not only did I have a working Nim
application, but it was a working Discord Bot.

The small compiled binary size, and the teeny tiny resource footprint that the application has when the compilation
is completed, is right on part with Rust and Go applications. The Nim language is very much like Python in that it is
whitespace centric. If you are already a Python or even a Rust or Go programmer, the syntax should be easy to pick up
on.

In a short period of time, in this first stage of testing a new language, not only was I able to get a working Discord
bot going, but I was able to add a few features, such as database connectivity using the built-in PostgreSQL wrapper.

Not only did Nim allow me to quickly create the application, but using a simple Dockerfile, I was able to ensure that
the bot application would run nice and smooth on my cloud hosting platform of choice.

All in all, I really enjoyed my first round with Nim, and I look forward to doing more with it.