---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Meteor

It's taking me a long time to get used to meteor. It's taking me a long time to get used to what it really is, how it works, and what I can really do with it. I understand the pieces well enough and can work with them individually quite well in fact! For some reason though when put all together into this Meteor framework package everything kind of falls apart.

## The Learning Trajectory

There are several reason why I think it's been difficult for me to grasp Meteor but I think the most prominent one has been understanding the program structure. Meteor and the rules and general style guide that I'm working in are quite strict about where things go. While historically I've done the bulk of my work spread over a single large file or two on a project such as a webpage, Meteor spreads that over four or maybe even five files in several differeny directories. The problem here that I have is that it's not quite intuitive. Of course, tracing back through the references you can eventually pick out where you need to edit and make additions. This isn't really sustainable though when you have to do this dozens of times as you bug fix and add new features. Really understanding the program structure is something that I think you absolutely need to iterate on and drill into your head before you really start working. Thinking "I need to edit this section" and knowing exactly where that specific file is to edit will immensely help with production.

## Connection Disconnect

Meteor is very well put together and separates things into their own sections so that you don't have to sift through a giant document to find what you need. It does this through a series of references to other files using templates. Then, from there you can adjust it's functionality using helper functions in your javascript code. It still is immensely frustrating to me to navigate my way through this series of nestings and references. I understand that while in the long run this is a way better way to do things so that changes can be made easily without affecting other parts of the app, I feel the layers are quite daunting to navigate. It's like having a puzzle. You know what you want the picture to look like and you know all the pieces fit together to make that picture but you spend so much time figuring out what the piece in your hand is and where it goes. For me that's my largest problem with Meteor so far. It's the disconnect that I have to understanding how the app works because of how interconnected it is.

## The Digits App

I've been currently working on an app called "Digits". It's basic idea is to work as a contacts address book and to start the proejct I worked off a template. First time install aside (which took a really long time) creating an initial mockup was surprisingly difficult. All we had to do was create some simple additions but I spent an excruciating amount of time with the problems I listed above. One of the things I wanted to add was a simple header image. Tracking down where to add the image was only the first part of the battle however. After locating where it went and making my img in the HTML, it wasn't showing. I realized that in that same file the nav bar was set to fix to the top of the screen hiding my image behind it. I ended up having to edit the Semantic UI class of that nav bar so that it wouldn't be fixed to the top of the screen. My picture showed! But it sitll didn't look right. There was epty space above and below it that I needed to get rid of. To fix this I had to make some inline CSS in the HTML to get rid of it. And herein lies my biggest problem with Meteor. There are too many moving parts.
