---title: "Build a game with 1 prompt using AI (ChatGPT o1, no code)"
video_id: "mkphDClhi5w"
youtube_url: "https://www.youtube.com/watch?v=mkphDClhi5w"
publish_date: "2024-09-18"
duration: "7:43"
duration_seconds: 463
view_count: 6315
author: "Alex Finn"
description: |
  Like, reply, and subscribe if you learned anything!

  Follow my X: https://x.com/AlexFinnX
  Subscribe to my newsletter: https://www.1percentbetter.io/subscribe

  Learn how to build a simple game with AI! No programming experience necessary! Beginner friendly! We use ChatGPT o1 to build a simple game in under 10 minutes. You can then use these skills to build any application or game you want.

  ⏰Timestamps
  0:00 ChatGPTo1 Intro
  0:54 Prompt
  3:00 ChatGPTo1 Response
  4:35 Cursor
  6:29 Run Game

  Prompt:
  Use pygame to make a game called "Pac Boy" very similar to Pac-Man
  * You are a yellow circle with an eye and a mouth. You are automatically moving forward.
  * You are in a maze.
  * In the maze, there are white dots you need to eat.
  * The character automatically moves forward. You use the arrow keys to change direction.
  * You cannot move through walls.
  * There is a red ghost that is also moving around the maze that you want to avoid.
  * The ghost should move along the grid, changing direction only at tile centers, to navigate the maze correctly without getting stuck in walls.
  * If it touches you, you die.
  * Use retro colors and a dark background.
  * Put a score counter in the top right that increments by 1 every time you eat a dot.
  * Automatically restart the game when you win or lose.
  * Give the code in a single file.

  Links:
  Cursor: https://www.cursor.com/
  Python: https://www.python.org/downloads/
  pip install pygame
  python3 pacmangame.py

  #ai #coding #programming #cursor #games #chatgpto1 #chatgpt

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "Prompting"
difficulty: "Intermediate"
audience:
  - "Engineers"
  - "Executives"
  - "Product Managers"
entities:
  companies:
    - "Cursor"
  people:
    []
  products:
    - "ChatGPT"
    - "Cursor"
    - "Make"
    - "o1"
  models:
    - "o1"
concepts:
  []
summary:
  - "# Build a game with 1 prompt using AI (ChatGPT o1, no code)

let's build a Pac-Man game using chat gp01 with a single prompt here we go I opened up chat gp"
keywords:
  - "ai-tools"
  - "chatgpt"
  - "coding"
  - "cursor"
  - "frameworks"
  - "make"
  - "o1"
  - "openai"
  - "product-management"
  - "prompting"
  - "workflows"
---

# Build a game with 1 prompt using AI (ChatGPT o1, no code)

let's build a Pac-Man game using chat gp01 with a single prompt here we go I opened up chat gp.com we're making sure we're choosing the chat gbt 01 preview model this is by far the most powerful AI model I've ever used in my life especially when it comes to coding other games I try to build with AI models before would take me hours and hours and tons of prompts to do to build the game I would have to edit every single little piece of the game prompt by prompt to get it done with chat gp1 I'm able to put in a single prompt to build my game we're going to build a Pac-Man game here follow along I'm going to put the prompt below once I'm done with it the key to building apps with chat gp01 is to give a good amount of detail so that it builds exactly what you want the the the model is super smart and super precise the more detail you can give the more accurate your app will be so let's start with this use P game to make a game called pack boy very similar to Pac-Man so I always recommend if you're building games for the first time if you're a beginner make sure to say use py game to make a game called packboy This is a library in Python which makes it super easy to build games I'll get into all the technical details soon but it's super simple now let's get into some of the detail of this game first detail I'm putting in you are a yellow circle with an eye and a mouth you're automatically moving forward so we're just building the general Pac-Man character you are in a maze so we're building the level in The Maze there are white dots you need to eat so we're building out the cookies that the Pac-Man's going to be eating again very simple step by step building out the details the character automatically moves forward you use the arrow keys to change direction so you want to be specific about the controls here you can make the controls whatever you want if you want to use WD you can do that as well you cannot move through walls so again even if you're building out your own Zelda clone your own Mario clone whatever you want make sure you're specific about what you want the character to do there is a red ghost that's also moving around the maze that you want to avoid so we building out the enemy with the prompt the ghost moves along the grid changing directions only at tile centers to navigate The Maze correctly without getting stuck in walls so we're telling the AI what we want the ghost to do as it's chasing us around the board the ghost touches you you die use retro colors in a dark background so we want to give it instructions how we want the game to look and feel if I want to give it a futuristic look to use neon colors we can do that I want to make it feel like an old school Pac-Man put a four counter in the top right that increments by one every time you eat a DOT so as you eat the cookies the score goes up now I can make a scoring system and then the last part of the prompt I put in here is automatically restart the game when you win or lose and give the code in a single file so this is really simple for us to copy and paste into our editor this is all you need to build an entire game with chat gp1 this is pretty incredible I'm going to hit enter now we're going to see what we get so this is taking what we put in this is taking the entire prompt it's going to spit out the code for us what's really incredible about chat gp1 that makes it different than any other AI model out there is it does reasoning it takes your prompt and solves it step by step typically when you're using chat GPT 40 or any other AI model you put in a prompt and then it does one thing and spits out a response with Chad gp01 what makes it incredible is it goes step by step and figures out what's the best way to respond to your prompt so for my game it's figuring out step by step okay let's build the game Let's create the rules let's build the maze let's build the characters let's build the scoring system it does it step by step it's able to reason with itself to build the highest quality product possible the reason why it took so many prompts to build this with other AI models it only does one thing at a time so you have to build out the game one prompt at a time but with Chad gb1 it's able to reason with itself it's able to spit something out step by step so you can get really complex responses like what we're about to get here you can see the entire thought process the AI goes through which is really really cool create the game navigate The Maze clarify the rules lay out the game lay out the maze Implement game restart map out the basics set up the scene adjust the game logic it's really amazing to see how this AI is able to think and come up with the steps for the game all right so now it's spitting out the code here you can see it write the code step by step which is really amazing to watch typically again this takes hours it's doing it in in seconds here you can see the maze it's building out here in the code and what we're going to do in a second is take this code put it into a code editor and run it which I'll show you how to do step step by step as well you don't need experience with that boom looks like it's done let's copy the code here now what I have open is cursor this is the most powerful AI tool you can find this is going to allow you to run any code you want using AI I'll have the link Down Below download it there's a free version use the free version you can do everything here with the free version once you open that up you'll see this screen now let's just open up a folder to put our code in all you have to do is just go on your desktop create a folder called Pac-Man okay so we opened up our folder let's do this let's create a a new file we will call this Pacman dopy this indicates that it's a python file we'll drop in our code that that chat GPT just spit out for us we'll hit save couple quick things we need to do to make sure this works hit if you're on Mac control till day key this opens up our terminal first thing you want to do is install python so if you've never run anything python on your computer before make sure you download python so go on your browser type in download python and make sure you install python onto your computer to get this to run once Python's installed in your computer we can do the next step we'll do pip install pame in the terminal this installs pame which is going to run the game itself hit enter on that and then once that's installed we can run the game so again make sure you have python installed then run that command I just put in there which will be down below all the links everything I'm doing will be down below and then finally we can type in Python 3 Pacman .p so Python 3 space then the name of our file and this is what's going to run the code before I do that if you learned anything here make sure you hit like make sure you hit subscribe and let me know in the replies what other games and apps you want me to build with AI all my videos about building stuff with AI I want to make sure I build stuff you want to see now we can hit enter and there you go look at that it is running we have we can move around Pac-Man we can collect cookies if you look in the top right the score is increasing and the ghost is uh chasing me around on the screen too it looks just like Pac-Man and again we built this all-in-one prompt without writing any code whatsoever which is pretty incredible let's see what happens if the uh the ghost hits me here uh and it resets the game sets the score to zero that's pretty amazing that was all with one single prompt one code file it gets it in there it starts running the game now there's a lot of other cool things you can do if you want to go back and improve this right if we want to go back now and we want to come in here we make updates we can do that so if we want to say add another two ghosts and make them purple and green we can do that if we want to change the scoring system if we want to add super cookies that are worth more points we can do that again when you have ai working for you you don't need to know code you don't need to know any of that the AI does the work spits out the code for you you're really the CEO of your own software company all done with one prompt Chad gp01 is pretty incredible I can't wait to see this integrated into more tools if you got stuck at any point during this also feel free to go in back into the chat GPT and let it know where you got stuck whether it's python not working anything like that you can just type in here and chat GPT will debug it all for you so really important to know
