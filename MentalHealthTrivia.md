---
layout: default
title: Mental Health Trivia Game
description: A trivia game that educates people about mental health. Made for Korak Recovery Academy in Apeldoorn.
---

This game was made for Korak Recovery Academy. They offer modules that help people in difficult situations work on their recovery. Korak asked me to make an online substitute for their website. They wanted to offer something that was easier to access than their existing modules and reach a different audience. The mental health trivia game educates people about mental health while remaining fun to play. <br>

My personal goal for this project was to get better at making games with the main purpose of being educational. CMGT (my study) has multiple classes about making games fun, but none about incorporating learning. I strongly believe that people learn best when they're enjoying learning itself. It motivates me to see people genuinly enjoy what they're learning about, so I wanted to get better at facilitating that. <br>

The game can be played on itch: [Itch.io/mental-health-trivia](https://brenna-mathu.itch.io/mentale-gezondheid-trivia). <br>

![In Game Screenshot](/assets/img/Mentale_Gezondheids_Trivia_Menu.png)

# Generating Concepts
Korak gave me the freedom to come up with the concepts myself. To do this, I first had to learn about the people who frequent Korak and empathize with the struggles they face. I used the empathy canvas to do this. <br>

Based on the empathy canvas I set up these functional and technical requirements:
- The product needs to help people understand themselves and/or their mental health issues better.
- The product needs to incentivise people to change their behaviour for betterment of their mental health.
- It needs to be relatively easy to code to fit the time frame.
- It needs to have a web build to allow the product to be showcased on Korak's website. <br>

I came up with three ideas based on these requirements, Korak chose the trivia game with questions about mental health. <br>

# Turning mental health facts into an engaging game
## General Design
Because a lot of people find learning about mental health dull, the trivia game has to be engaging. I compared three trivia games to see what techniques they used to engage the player. I then used the Moscow model to prioritize these features and others I could think of, the must haves and should haves were implemented. The must haves are questions with a good difficulty level, good visuals and references to the other Korak courses. The should haves are an interesting power-up mechanic, sound effects and question categories. <br>

Because the goal is for the player to learn, all the questions also explain why that answer is correct or not and offer links to additional learning resources. The game functions like an 'infinite' loop, the player gets a point and some coins per correctly answered questions. The game keeps a high score to motivate the player and the powerup that halves the possible answers can be bought with the coins.<br>

The UI is based on the colour scheme Korak uses. It's centered on the questions and answers and the contrast draws attention to the answers as well.<br>
![UI Design](/assets/img/Mentale_Gezondheids_Trivia_UI.png)

To provide clear feedback to the player, the clicked answer and the trim around the explanation screen get coloured and sound effects play.<br>

## The Questions
To make sure people learn the questions had to be simple, but difficult enough that most people don't know a lot of the answers yet. The wrong answers aren't obvious or funny to ensure that people really have to think about the question. There aren't any trick questions, as that mostly leads to confusion and frustration. <br>

I looked through all the courses Korak offers to find topics to write questions about. Korak asked me not to write questions about specific diagnoses, they want the game to be about general recovery. Based on the topics I found in their program I looked up trustworthy articles and studies that I wrote questions about.<br>


# Playtesting
The product was tested on the people at Korak to ensure it fits the target audience. People need to find the game fun, they need to learn from it and it needs to fit in with Korak's branding and modules. I tested it on other people first to get mistakes out to allow the results of the playtest to only show if the product works on the target audience. These are the reults of the playtest at Korak:

![Playtest Results](/assets/img/Mentale_Gezondheids_Trivia_Playtest_Results.png)

People thinking they’re learning isn’t the same as actually learning of course, so the next question asks them what they learned to confirm it. My observations also conclude that people do learn, though some quicker than others. They answer correctly to questions they previously got wrong and often proudly tell me they remember this.

### You can find the game here: [Itch.io/mental-health-trivia](https://brenna-mathu.itch.io/mentale-gezondheid-trivia)

[Back](./)