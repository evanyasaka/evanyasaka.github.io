---
layout: project
type: project
image: images/gundam-logo.png
title: Build Manoa-Quest
permalink: projects/manoa-quest
date: 2017
labels:
  - JavaScript
  - MongoDB
  - Meteor
  - Web Development
  - Collaboration
summary: In one month myself and a two other people built a webapp that aimed to gameify classrooms in order to encourage students to become motivated with their classwork and engaged.
---

## The Beginning is Always the Hardest Part
What's the number one thing that stops people from finishing a project or not following through with an idea? It's not group dynamics, nor is it motivation, or even lack of ability. It's starting. Tons of projects never get off the ground simply because people can't take the leap of faith and start. Fellow colleagues Kirk and Christie worked with me to create a webapp that we named Manoa-Quest whose goal was to create an interactive classroom where students would be more motivated to keep up with their work, and more engaged with the content by providing them with goals to complete in a role playing game style environment. Just this concept was our first hurdle. Deciding on a subject and the scope was our first major goal to tackle. 

## Designing the Goal, Scope, and Workload
When I first proposed the idea of gameifying classrooms to the group the general consensus was quite positive. With no project idea in mind we were all quite open to something to latch on to. The difficult part was not figuring out what to do however. It was figuring out how much to do. Early on in to development we had several back and forth discussions trying to nail down the minimum viable product that we'd like to produce. Initially I had many grandiose plans about what I wanted the app to be capable of. I wanted to be able to have a character creator, animations, and sound effects. I really wanted it to feel like you were playing a game. My group members on the other hand had different ideas. While we all agreed on some simple core functionality such as turning assignments into "quests" we had drastically different ideas on how far to go. In the end, Christie intodruced the idae of "minimum viable product". She said that since there was a set of core functionality that we wanted and were reasonably sure we could achieve, that should be our immediate goal and to add these other features we wanted into  list that we could re-evaluate once we've met our MVP. It was a great suggestion as we could have likely spent days discussing things in circles. This let us start working while keeping future ideas in mind.

We decided that we wanted the app to stylistically be similar to a game, to have students able to complete assignmetns as if they were turning in a quest, and to have a professor or TA able to manage the creation and rewards for quets. Additionally, we wanted to have a leaderboard showing the top performing students.
  
 ## Milestone 1
 Our first milestone set out to design mockup pages of the application.
 
 I had a basic template version that I had made stored in a private repository on my github account which I decided would be a good starting point for us to start collaborating on. After making our group's github organization page and setting up our project website I forked my private repo into a repo that we would collaborate on in our organization. Mockups went quite surprisingly quite smoothly. We were all reasonably comfortable with what we were doing and were able to create mock-ups for pages we had decided we would need. As an aside, I cannot stress how effective of a team-bonding experience getting yakiniku together is. Over food we were able to discuss the project very candidly and openly without the constraints of it feeling like "work". We had a working mockup version of the site ready to go quite quickly and were ready to move on to the next milestone when our first major hurdle came along: issue driven project management.
 
 ## The Problems of Forking
 One of the constraints we had to work within was the project management philosiphy of issue driven project management. This meant that for all the things we needed to add or change on the app we needed to make an issue in github and track whether or not they were in a backlog, in progress, or already completed.
 
 The big problem however was that because I had forked the repo from my private version, we could not make issues within the organization version. Since the app was based on another repo, issues could only be made in the original repo meaning that we wouldn't be able to track them in the organization's project management.
 
 In order to combat this we had to completely remake the repo and move towards that style of project management starting with Milestone 2.
 
 ## Milestone 2
 For this milestone we set our goals a little bit too high. Initially we had all set out to try full stack development where we each took a page and worked on the whole design of that page from the top down from interface to database. Because of the major functionality goals that we had however, we were wasting so much time going back and forth between trying to make sure we were on the same page with database design and keeping styling the same that we decided it just didn't work for us. Thankfully our team was a fantastic combination of specialties that really aligned well. Christie had done a lot of full stack development with a focus in design and working with GitHub on things like merge conflicts and workflow, Kirk was really good with databases and data design, and I was very comfortable with JavaScript and programming. In the middle of the milestone we completely flipped our project development approach upside down to accomodate each persons skills.
 
 This worked so fantastically that I'm surprised how smoothly it went. Anytime I needed to make a change ro the database I'd let Kirk know and he'd modify the schema and relay field names and changes to it and how I could reference it. Anytime I needed a new page I told Christie the specs I'd want and she'd make it for me. My job was to connect it all together. To work on the dataflow and tying the frontend to the backend was really enjoyable for me. It gave me a very good insight in to the necessary scope into much larger projects and how daunting it could be.
 
 The one place where I tripped up was implementing our CAS login system. I just could not figure it out. Luckily however, in his downtime Kirk was looking through an app we were referencing called BowFolios that had a running system for that. He was confident that he understood how it worked so he implemented it and showed me how to work with it.
  
  Our milestone two major goals were to implement that CAS login system, and design the database schema and make sure we could reference it from the app and we met that goal with flying colors.
  
 ## Milestone 3
 For our final milestone we had to fill the databse with dummy data so that I could make sure functionality worked. We implemented it by having the app load sample data from a file if the databases were empty. My job for this milestone was to make sure the pages could pull data from the database and that when actions were taken they would take you to the correct page or modify the DB in some way. We also needed to add the leaderboard still as I wasn't able to get to it during the second milestone. Thankfully the most difficult part about this was figuring out how to filter results from database queries to show the proper information. Since we were so far into the project changing the datastructure of the backend would have meant redesigns of a lot of other modules in the project. I was able to finish all of the functionality quite quickly so I was able to move on to one of our stretch goals which was to make some custom avatars for people. Ideally this would have extended into a character creator I did not have the resources or the time to filly flesh the idea out.
 
 Once I finished the functionality, Christie worked on the final styling and deployed our app to Galaxy where all three of us tested it along with a few of Christie's friends.
 
## Lessons for the Future
This was a great learning expereicne as while I've done collaborative work in the past, it's never been this integrated before. There are many things I think we could have done better such as a better balance of workloads between everyone, and more in person discussions. I wish we met our stretch goals and had we been able to devote more time to it I think we could have really made something truly great even though I'm satisfied with what we've presented.