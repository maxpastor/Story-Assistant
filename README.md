# Story-Assistant
This is a GPT based short story writer

## The idea: 

Before working in Tech I was studying screenwriting and always had interesting stories in the back of my head. The issue was that developping an idea and writting a script where 2 different things. And it's even more difficult when your native language is not English. 
When ChatGPT came out, the first thing I did was to brainstorm with it to work on stories I haven't touched in 10 years. 

This repo and the notebook inside aims at making a system that can write a full story (short for now), using GPT-3.5 or GPT-4. 

## The System:

The system is simple but efficient. GPT-3.5 or 4 is good at doing 1 task at a time. If you ask it to write something it will do it but it will miss some more specific details. 

For example, it can write a paragraph that will match the story outline you have, but the style or quality of the writing will be debatable. 
### So the idea is to have 1 assistant write something and another refine it, so the focus is not on writting from scratch but on polishing ! 

This works kind of well, I suggest you try it yourself. 

## Cost: 
If you're using GPT3.5 it is fairly cheap (a few cents). For GPT-4 it's more expensive. 
Also, the stop token "END CHAPTER" is not being generated on the 2nd system in the notebook, so ... I have to find the reason why and find a fix. 
The consequence is that it will generate a first chapter that's the size of a full book, which will cost you money forever until you stop it. 


# Disclaimer: 
Even though I work at Amazon Web Services, this is a personal project / repo. Amazon is not responsible or involved in any of this code. 
