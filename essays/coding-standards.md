---
layout: essay
type: essay
title: Professionals Have Standards
date: 2017-02-09
labels:
  - Programming
  - Development
---

## Professionals Have Standards

I used to play a lot of a video game called Team Fortress 2 and one of the best things that came out of that game were animated shorts featuring each one of the nine playable characters. Particularly I enjoyed playing the Sniper and in his animated short we explore some of his motives and personality. My favorite line in that short however was "Professionals have standards." Like those of us who program, every professional should understand the importance of standards.

Okay, so that reference was a bit of a strech. Next time I'll try and limit my pop-culture referenmces to something a bit more relevant. This, however, does not diminish by any amount the absolute importance of standardization.

When I first lerned to program I was completely self taught and a naive little baby in the world of programming. Random indentations, same line blocks, multi-line strings -- I probably broke every single style guide's rules over just the couse of one afternoon. I would constantly write something and get it back formatted completely differently from where I left off. It was jarring, certainly, but it didn't occur to me until several months down the line that it was actually esier to read and understand! This is one of the many benefits to coding standards.

In a nutshell adhering to standards provides us with several extremely important benefits.

* Easier to read
* Easier to collaborate
* Quicker maintenance and problem solving
* Less confusion

Now these were pretty broad however anyone who has ever spent time learning to cook can immediately understand how important it is that everyone is on the same page, using the same tools, and using the same measurments. While learning a recipie you immediately know what three cups of X ingredient means or what result to shoot for when being told to simmer something. This is just like in coding. For instance, although somewhat broader in scope, in ECMAScript 6 you know exactly that when a value is declared with ```const``` it will never change. When you start to think of program code as a recipie, then setting some baseline standards just makes sesne. Everone who looks at your program recipie and is familiar with the style you are using can follow along. When you need to make a change, you know exactly where to look, how to change it, or how to fix something because the style guide specifically tells you exactly what you need to do!

## I thought ESLint was supposed to have no static!

Although it's true that ESLint discourages the usage of some static identities, this isn't the kind of static I'm talking about. One of the biggest hits against standardization is that often people get caught up in the nitty-gritty of style guides. Specifically the parts that micro-manage what many consider to be 'trivial' things. For instance, according to ESLint, had I used double quotes in that last sentence ESLint would have had me burned at the stake for my transgression! What is the difference between single quotes and double quotes and why is it so important that a rule had to be specifically made for it?

To argue for double quotes many people are already familiar with double quotes around strings because of their existing language. Additionally what happens if I try to use single quotes around the sentence ```I can't go they're too cool and won't like me```? In this case you'll have to escape all the contracted words whereas if it were surrounded by double quotes that wouldn't be a problem at all. In fact in JSON you MUST use double quotes. 

So what gives? 

The long and short of the answer is "I don't know." Sometimes there are little things here and there that just don't make sense or seem superfluous and honestly, that's okay in my book. There are many, many, many other benefits to using standardized guides that for each one of the superflous cases there are ten other cases where the style guide helped you instead. When everone is cooking using the same measurments, the same terminoligy, and the same techniques, collaboration, sharing, and efficiency just become second nature rather than an effort in frustration.
