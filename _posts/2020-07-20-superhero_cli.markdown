---
layout: post
title:      "Superhero CLI "
date:       2020-07-20 19:38:34 +0000
permalink:  superhero_cli
---

**
// My program **

I’ve officially finished my very first project as a Flatiron School student, the CLI Data Gem Project. So do I qualify as a software engineer now? 

My program allows a user to enter the name of a superhero (from a predefined list) they want to learn more information about. 

```
Welcome to the ultimate Superhero App!
Enter the name of the superhero you'd like to learn more about or enter 'exit'.
1. Aquaman
2. Batgirl
3. Batman
4. Deadpool
5. Firestorm
6. Hulk
7. Mystique
8. Phoenix
9. Spider-Man
10. Thor
```

While my program might suggest I have an affinity for superheroes, I surprisingly do not but nevertheless it was a fun idea! 

Once a user enters the name of the superhero, the hero’s profile is displayed in the terminal. 

```
-----------Superhero Info-----------
Name: Lex Luthor
Full Name: Lex Luthor
Alter Egos: No alter egos found.
Place of Birth: -
Occupation: Owner of LexCorp
Powerstats:
 - intelligence: 100
 - strength: 53
 - speed: 25
 - durability: 65
 - power: 68
 - combat: 70

Would you like to see another superhero? (y/n)
```

The program then asks the user if they'd like to see another superhero. The user can either enter the name of another superhero or type ‘exit’ to stop the program. 

**// Approach**

When I first delved into the project, I was planning on creating a completely different app using scraping but after a frustrating attempt and losing the majority of an entire days worth of work, I abandoned my original project idea and enlisted the help of an open API instead. 

I found the Superhero API from a simple Google search for Open APIs.The API required me to sign into my Facebook account in order to get an Access Token. From there, it was pretty easy to connect my program to the API using HTTParty.  

Initially I struggled a bit with figuring out how to pull the data out the JSON response from the API but thanks to an incredibly helpful student in the #cli-data-gem-project slack channel, I was able to figure out how to pull it correctly. 

**// Advice**

Below is some advice I would have given myself if I had superhero abilities to time travel and warn myself. If you’re reading this before you start your project, you are one-step (atleast) ahead of where I was when I started my project. 

First and foremost, revisit Git commands and how to save your work to Github. Do not do what I did and spend hours thinking the Sandbox IDE is going to save your work. Save early, save often. Memorize or write down these commands: 

* git status
* git add -A
* git commit -m “<enter your commit message here>” 
* git push 

Secondly, join the #cli-data-gem-project slack channel. Students in that channel are going through exactly what you are and are so incredibly helpful when you get stuck. Remember, AAQ can’t help you with your project. 

Lastly, take advantage of the instruction.learn.co video lectures. For project setup, I recommend following Beth’s Eden Projects (Part I) video over the Daily Deals video. Her projects are a bit more complicated than the level required of our first project so I’d only use it as a model for setting up a project and then move on. 

Keeping my fingers crossed that the first project review isn’t too brutal and looking forward to setting up my local environment and moving onto SQL next. 

‘Til next time! 


