---
title: Solving the Jetbrains Quest
date: 2020-03-10T18:24:57.500Z
description: Solving the Jetbrains quest for a free 3 months of Jetbrains products.
categories:
  - Jetbrains
  - Chiper
  - CTF
tags:
  - Jetbrains
  - CTF
  - fluff
---
Recently Jetbrains released a quest for us to follow over at Twitter\
<https://twitter.com/jetbrains/status/1236986174075482113?s=20>

> JetBrains Quest begins… [\#JetBrainsQuest](https://twitter.com/hashtag/JetBrainsQuest?src=hashtag_click)
>
> `48 61 76 65 20 79 6f 75 20 73 65 65 6e 20 74 68 65 20 73 6f 75 72 63 65 20 63 6f 64 65 20 6f 66 20 74 68 65 20 4a 65 74 42 72 61 69 6e 73 20 77 65 62 73 69 74 65 3`

It's evident that the first part is in hexadecimals so we can easily translate that into text and end up with

> Have you seen the source code of the JetBrains website?

Cool, so let's head over and check out their website source code. Looking trough it you will end up with a html comment that reads as the following

```
Welcome to the JetBrains Quest.

What awaits ahead is a series of challenges. Each one will require a little initiative, a little thinking, and a whole lot of JetBrains to get to the end. Cheating is allowed and in some places encouraged. You have until the 15th of March at 12:00 CET to finish all the quests. Getting to the end of each quest will earn you a reward.
Let the quest commence!

JetBrains has a lot of products, but there is one that looks like a joke on our Products page, you should start there... (hint: use Chrome Incognito mode) It’s dangerous to go alone take this key: Good luck! == Jrrg#oxfn$
```

Easy enough, the code provided will be useful later on. Let's check out the products pages (it's important that we disable any ad-blockers here or it might not show up). You will now find a product named "JK".

Pressing the product we will get asked to provide all primes between 500 and 5000 and then provide the answer in the following link https://jb.gg/###

This will lead you to the following image