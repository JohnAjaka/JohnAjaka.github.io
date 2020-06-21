---
layout: post
title:      "CLI Data Gem"
date:       2020-06-21 21:53:27 +0000
permalink:  cli_data_gem
---


For our first project, I decided to make a program that can help new players in my favorite game, League of Legends. The game has a huge roster of over 140 characters known as champions, and new players can find that super overwhelming. Having to open up your browser and search online for info about champs can be a draining experience and cause player fatigue, but with my program we can find specific info on a champ quickly and easily. 

One of the problems I ran into is when a player inputs a champ name that simply doesn't exist, what happens? I hadn't learned in our curriculum how to verify a link as valid, so I went online looking through stack overflow posts to see how I could go about it. After some quick searches, I found a process that uses the open-uri class to validate a web page by outputting a code of 200 for a valid page. I set up an if statement in my code within a valid_champ? method that checks for the 200 code, and will start the process over if it doesn't find a 200 code.

After miticulous scraping work, I was able to get the program functioning on a basic level. It doesn't necessarily output everything I would like it to, and I'm sure with some fiddling a user could find some bugs, since the wiki page is old and in some places not necessarily uniform, but this is my first project. Errors and mistakes are a fact of life, just like they are a fact of coding. I'm so excited to share this with my fellow learn cohort-mates and teachers, since this is my first totally my own code. On top of that, a lot of my friends in the league community find it to be pretty cool, which I appreciate whole-heartedly. Looking forward to review, and to get some feedback on how to make better, faster, and more elegant code for the real world.
