---
layout: essay
type: essay
title: The Right Question
date: 2017-01-26
labels:
  - Programming
  - Help
  - Development
---

## Road Blocks

We've all been there at one point. We're working on a project and getting into the groove of things. You're adding feature after feature and bam, two more things off the checklist. You move on to the next one expecting to knock it out like its predecessors when suddenly errors everywhere. You look at the errors - *"Oh, simple!"* - you think to yourself. You just mistyped a variable. You quickly fix it and then boom -- another error. This time though it's much more cryptic. As programmers, we would love to give verbose and meaningful error codes and descriptions but realistically we can't cover everything. You go back, check your code. Make sure every variable is typed correctly, you have semicolons everywhere, and you closed all your brackets, parenthesis, curly braces, and other curvy lines. 

> *"It should work!"* - Every Programmer Ever

You run it again one more time in futility and question where it all went wrong. You stare at it, Google it, and after several unsuccessful suggestions you decide to take things into your own hands and ask the question yourself.

## There Are No Stupid Questions

This statement was drilled into every student's heads when I grew up going to school in Hawaii. I'm sure a similar sentiment has been expressed elsewhere and they all mean the same thing. You should always ask a question no matter how simple or trivial it is. You might not be the only one who needs clarification! Perhaps by asking your question you can help someone else too. Even if not, it's better to ask than to fall behind right? In a school setting, sure, this is a great mentality. You're all there to learn and the lecturer or teacher is expected to be reasonably knowledgeable on the subject enough to answer your questions. Discussion can lead to clarification if your question is lacking, and the subject can be expanded upon if it's relevant. 

There are no stupid questions.

Yes, there are stupid questions. Semantics aside, once you start looking for expertise online on forums, newsgroups, developer networks, and other such locations how you ask your question is just as or even more important than the question itself. You are but one of thousands of developers asking all sorts of questions at the same time. How do you make sure yours is the people with the knowledge read yours and take the time to answer? It's simple -- you ask a smart question.

According Eric Raymond, your question should follow several guidelines such as:

> Use meaningful, specific subject headers

> Make it easy to reply

> Write in clear, grammatical, correctly-spelled language

> Send questions in accessible, standard formats

> Be precise and informative about your problem

> Describe the problem's symptoms, not your guesses

While these are not all the guidelines that were listed, they can be generally summarized into three categories:
  * Ask your question in a precise and meaningful way.
  * List symptoms verbosely and do not interject your own conclusions.
  * Be courteous and mindful of the people replying to you.


## The Good
Let's look at the question asked 
[here](http://stackoverflow.com/questions/41736767/java-8-boolean-logicalor-method) for example.

This example isn't a perfect candidate to highlight every aspect of Raymond's guidelines but it's quite good. Right off the bat we see in the subject header they list the platform the question is referencing, the version that's being worked on, and the object that is being questioned. This could be made better by also expressing the deviation of the object per Raymond's *object-deviation* model however. The first thing I'd think about when looking at this question is *"what about it?"*.

Within the question's description however there is some good meaty stuff that is compelling and can be worked with. The author expresses a change that was made in Java 8 about the addition of the Boolean.logicalOr method. He immediately gives an example of it being used and then clarifies the missing information in the header by directly asking his question: *"Why were they needed?"*. He even gives a counter case and looks for guidance on standard preference.

I like this question a lot because while the header wasn't as good as it could be the description was clear, concise, easy to read and understand, and informative for someone who may have not even known about the addition of the method to begin with. It is clearly shown that the question was asked well enough for the question to be answered with a clear and exact answer merely eight minutes after it was asked. The question even spawned a reply about a niche case where the slight difference in notation between two examples would prove relevant.

## The Bad
Now let's look at [this](http://stackoverflow.com/questions/32480662/sphinx-search-in-codeigniter) question.

Let's start off with statistics. As of this writing, the question linked here was asked one year ago, was viewed 336 times, and eleven replies with the only "answer" being a reply from the author 

Here the subject header doesn't indicate any versions, or problems, just an action someone tried to do that presumably didn't work. In the description, their language is acceptable but not good, there are grammatical errors and the writeup isn't formatted or verbose at all. The author leaves a tinge of arrogance by saying something to the effect of *I've done this before* and even goes to quote a place he did it in with no code or logic to give an example for others to reference. The kicker though is that the author did not even include the code that was being worked with. This is like asking someone how to fix a computer without being able to see or inspect the machine in question. It's doable but it is frustrating and an exercise in patience. Basically, it's like doing over-the-phone tech support with a bad customer. 

The replies are indicative of the kind of response we'd expect from something like this. In fact, the very first reply is 

> *"please share the actual code you running"*

## The Acceptable

We will inevitably have to ask a question at some point and while not all our questions can be stellar and incredible, following the guidelines laid out by Raymond will ensure that the question can be answered promptly and precisely. I've come to realize over time that programming and computer science in general is quite reliant on good communication skills. Clarity is key, and preciseness is necessary for you and everyone else to keep typing away at O(lg n) efficiency! 

