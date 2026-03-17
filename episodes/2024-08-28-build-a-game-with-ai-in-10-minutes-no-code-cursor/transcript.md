---title: "Build A Game With AI In 10 Minutes (no code, Cursor)"
video_id: "2fHPB_6ZXvM"
youtube_url: "https://www.youtube.com/watch?v=2fHPB_6ZXvM"
publish_date: "2024-08-28"
duration: "16:11"
duration_seconds: 971
view_count: 41003
author: "Alex Finn"
description: |
  #ai #coding #programming #cursor #games
  Follow my X: https://x.com/AlexFinnX
  Subscribe to my newsletter: https://www.1percentbetter.io/subscribe

  Learn how to build a simple game with AI! No programming experience necessary! Beginner friendly! We use Cursor to build a simple game in under 10 minutes. You can then use these skills to build any application or game you want.

  Timestamps
  0:00 What are we building?
  0:19 Tools we are using
  1:27 Create a project
  2:06 Cursor Settings
  3:30 Set up React
  5:28 Application launched!
  6:00 Start building the game
  10:33 Game launched!
  10:44 Debugging
  12:57 Game works!
  13:52 Customize game

  Cursor AI Rules:
  "DO NOT GIVE ME HIGH LEVEL STUFF, IF I ASK FOR FIX OR EXPLANATION, I WANT ACTUAL CODE OR EXPLANATION!!! I DON'T WANT "Here's how you can blablabla"

  Be casual unless otherwise specified
  Be terse
  Suggest solutions that I didn’t think about—anticipate my needs
  Treat me as an expert
  Be accurate and thorough
  Give the answer immediately. Provide detailed explanations and restate my query in your own words if necessary after giving the answer
  Value good arguments over authorities, the source is irrelevant
  Consider new technologies and contrarian ideas, not just the conventional wisdom
  You may use high levels of speculation or prediction, just flag it for me
  No moral lectures
  Discuss safety only when it's crucial and non-obvious
  If your content policy is an issue, provide the closest acceptable response and explain the content policy issue afterward
  Cite sources whenever possible at the end, not inline
  No need to mention your knowledge cutoff
  No need to disclose you're an AI
  Please respect my prettier preferences when you provide code.
  Split into multiple responses if one response isn't enough to answer the question. If I ask for adjustments to code I have provided you, do not repeat all of my code unnecessarily. Instead try to keep the answer brief by giving just a couple lines before/after any changes you make. Multiple code blocks are ok."

  Commands:
  npx create-react-app flappy-bird
  If it doesn’t work: sudo create-react-app flappy-bird
  cd flappy-bird
  Np m start

  #ai #coding #programming #cursor #games

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Tools"
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
    - "Claude"
    - "Cursor"
    - "Make"
    - "Sonnet"
  models:
    - "Claude 3"
    - "Claude 3.5"
concepts:
  []
summary:
  - "# Build A Game With AI In 10 Minutes (no code, Cursor)

I'm going to teach you in under 15 minutes how to build your own video game with AI"
keywords:
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "coding"
  - "cursor"
  - "frameworks"
  - "make"
  - "product-management"
  - "sonnet"
  - "tutorials"
---

# Build A Game With AI In 10 Minutes (no code, Cursor)

I'm going to teach you in under 15 minutes how to build your own video game with AI. No experience necessary, no programming knowledge necessary. You'll be able to take this game, put it on the internet, sell it to anyone you want, start making money, and build your own online business. Let's get into it. Boom. I'm over here now. Okay, let's get into it. Uh, first thing we're going to do is talk about the software you're going to need. The only thing you're going to need to download for this is Cursor. Cursor is the hottest piece of AI software on the block. It's the most powerful application of AI I ever used. Uh, completely free. Download it for free. Basically, what it does is it allows you to create code with AI. No knowledge necessary, very easy, and get applications up and running in minutes. It really is incredible. So, here's the website, cursor.com. Go in here, download it for free. Uh, there is a free version which will allow you to get started. You can use the twoe trial. Make sure you do that for this. If you fall in love with it, then you can move up to $20. The $20 version allows you to do a little bit more coding, uh, get a little bit more AI use out of it. I personally think it's worth it. They're coming out with new beta features for it, which is incredible. But hey, for your first project, you can go with free, test out the trial, you know, get your get your wings under you. Get build your AI muscles up and get started. So, download this, get that installed, and then we will actually move into the cursor application right now. Okay, we got Cursor installed. Let's get into Cursor and start building our game. Uh, this is what you're going to see when you open up Cursor. What we're going to want to do is select a folder to put our game in. I come in here, open folder. As you can see here, I already have a folder I made on my desktop. Make a folder wherever you want. I called it Flappy because we're going to actually be making a Flappy Bird type game that we can edit and make and launch. I click open. It is now good to go. Before we start building the game, let's actually real quick talk about some settings. It's important we have the right settings for cursor set up. So, I'm going to open up settings here. You're going to want to make sure your settings are all properly set up. I'm going to include all of this in the description if you need any of it. First thing you want to do is give some rules to the AI. This is really important because these rules for the AI will make sure it gives you the best code possible. So take this from the description, paste it into your settings. You're good to go. Next, we're in models. So when it's using AI to generate its code, it's using the best models. Claude 3.5 Sonnet is the best, but I have the other one set up just in case it needs to use them to save us time. Then you want to go into features. Here you have some features you can set. Make sure yours matches all of these. Trust me when I say this, this is going to make your experience as powerful as possible. So, make sure you got enabled fast. All of these are enabled. And then what you can see here on the right hand side is all the settings I have enabled or disabled. Make sure you go into your settings. You can pause it right here and make sure your settings and cursor match this. And then last, we go into beta. We want to enable composer. Composer is a brand new feature for cursor that actually is probably the most powerful feature it has. It makes generating code and implementing it as fast and easy as I've ever seen in my entire life. Uh, and then make sure all your settings match up here. So, let's close out of the settings now. Now, we're ready to start building our game. What we're going to do is first we're going to set up the technology behind the game. So, we're going to open the terminal. If you're on Mac, this is controll key. That opens up the terminal at the bottom. And what we're going to do is we're going to install a technology called React. React is the most popular web app technology going on right now. It's the easiest way to build and launch apps. I'm using this for this game just because once you get used to React, you'll be able to build really any application you want. We're going to start off by installing React down below. Uh feel free to take the commands I'm about to put in from the description and paste it into here. So, what I'm using here is npx create React app flappy bird. Basically, what that's going to do is that's going to create a React application for us. It's going to name it Flappy Bird. Hit enter. If you get an error here after you hit enter, that means you might not have the right permissions. So, put in pseudo before that command and that will make it work. I'll include both of those before just in case you get that error. So, that is building the React app for us. Now, we'll let that build out here and then we'll go into the next steps. We are nearly seconds away from using AI to build our application. This is going to be awesome. This will also be a good time to tell you if you want to learn how to build more applications, if you want to learn how to build more games, if you want to learn how to make more money on the internet, then make sure you hit subscribe below. I'm going to be creating a ton of content like this moving forward. And also make sure to turn on notifications. So, looks like we got our React application installed. Now, we are going to actually go into the Flappy Bird folder that we just created. So, cd Flappy Bird. Make sure you copy and paste that in. Hit enter. We are now in our new game. If you look over to the left, you can see the code's been built out for us. We have kind of our baseline React application. Now, if I type in npm start, it will actually start the application. So, we'll get that going. And then what you can see here is your first application running. Congratulations if this is your first time programming. You just built your first online web app. Incredible. There it is running for you. Mind-blowing, right? Obviously, this isn't too impressive an application, but you should be proud of yourself that you got up and running. You built a web application. You're now ahead of like 99% of people. So, now let's get into actually building the game. So, move that window over on your monitor, minimize it, do whatever you need to do. Let's get back into cursor here. And what we're going to do in cursor is we are going to hit commandshift I. What this is going to do is open up our composer. This is where we can have the AI build entire applications for us in just a couple sentences. So, what we're going to do here is we're going to instruct the AI that we want to build a Flappy Bird type game that we can start playing around with and editing. So, what we're going to say here, and I'll put this down below so you can copy and paste it if you want, but I recommend typing this out for yourself just so you get the muscles going in your fingers and you learn how to think in the way of AI. But let's do this. Let's say I want to build a Flappy Bird game using React. Make it as beginner friendly and simple as possible. Implement it in my current file structure. So before I hit enter here, uh I just want to kind of go through what I just did here. I'm basically instructing the AI in plain English, right? I'm not using any code, anything technical here. I'm saying, "Hey, I want to build a Flappy Bird game using React, which is the technology I just showed you how to install. I'm making sure it's as beginner and friendly as possible because obviously this might be our first time using code. I want to make sure this is simple for you to understand as possible. And then we're telling it to actually implement the code for us." Enter. Here we go. The AI is doing the magic. So what you see here is actually the AI building the files for us. So you can see the different files here and then it's putting in the code in those files for us as well. Um this is pretty amazing. Here you're seeing an entire application being built in literally what was that? 10 seconds less than 10 seconds. Typically this would take people 2 days to do. We just did it in 10 seconds. When they talk about AI changing the world this is what they're talking about the efficiency here. We just took something an entire dev team had to do and we did it in basically two sentences in under 10 seconds. Pretty incredible. What I want you to do is actually go through and what it did here is it explained how all this worked. It explained the files it set up, what each file does, the code it put in there. Um, but what I want to do is I'm just going to go ahead and accept all. I really recommend as you're doing this your first time to go through and actually read how everything works so you can learn along the way. Learning is very important here too. Uh but basically what you need to know is it built a file for every component of the Flappy Bird game, right? The bird in the Flappy Bird, the pipe, the game, uh and then the main application code. App.js in React applications is always going to be the main application code. Uh styles.css CSS code is always the styling makes things look pretty. And then index.js. Uh, it built all that out for us so that we can build this Flappy Bird game. I'm going to hit accept all. Accept all implements the code. Boom. All that code's been made, put in our project. So, if I come back here, I look on the left hand side. You can see they built out the code. The only issue here is uh it didn't actually put it in our file structure. So, we can fix that really quick. Let's do this. Let us copy components over to source. Boom. That's in there. Now, we'll take the app.js code. Copy it. Put it in our old app.js code. index.js. Take that. Put that in the new index.js. And then take the styles.css. Take that and put that in our existing styles.css as well. Uh, we can take all that. We can make sure we save it. So, let's go into each one of these new components. Do command S, command S, command S. That saves it and runs it. And then let's go into the other files we just built. app.js, command S, index, index.js, commands. Let's also here, one thing I noticed is let's make a styles.css file there. And then we can take this and put it into styles.css. Let's go ahead and delete the old code that it put in as well, just so we make sure we're working on the right code here. So, I'm going to delete the source. Move that. So, we're keeping the source that's in our application, not that extra one that was made. Now that we got the code cleaned up, let's test out the app. So, I'll pull it over here. Boom. We got a Flappy Bird game. This is pretty awesome. This was all just from two sentences all built out. Let's start it up here. Okay, looks like we got some issues. The ball's moving up, but the pipes aren't moving to the left. Let's fix this. Let's debug it. See, I'm not editing any of this out. I want to make sure you see how can see how you can fix bugs in here. See how you can iterate on the AI and make the game better. Okay, let's go back into the composer and start giving it some instructions here to fix the issues. The ball in the game is only moving up when I click. I'd like to use the space bar. And the pipes aren't moving to moving. Let's spell that correctly. Huh. Moving to the left. Boom. Let's see what it says. Got it. Let's fix the space bar control. Make the pipes move. Here are the changes. Okay. So, it's generating some new code. So, first we are in game.js. We got some new code here that is changing it so that it is the space bar that moves the ball. Cool. I didn't like the clicking. When I play Flappy Bird, I want to use the space bar. Um, add handle key press on click. And then it moves the pipe position. All right, let's accept this. Accepted. Go into game.js. Save this. Let's pull open the game. Okay, the spacebar fixed. The space bar is fixed. The pipes still aren't moving. The pipes still aren't moving. Let's go back and we'll fix this. All right. Uh, let's fix this. Okay, we'll go. Uh, the ball has been fixed, but the pipes still aren't moving to the left. I apologize for the confusion. Let's fix the pipe pipe movement issue. The problem is that the pipe components aren't using the pipe position state. Here's how to update the code. Okay, so it's updating game.js. You can see some of the code it's changing here. Again, spend a minute or two, look at the code, see what's changing just so you can learn how all this works. And then we can go into pipe.js and we can see what's changing here. They're changing the pipe there. And we're changing the game code here. Okay, let's accept all. Let's move it back in. See how it's working. Oh, there we go. It is working. You can see the pipes are moving to the left. The space bar moves the ball. The score goes up every time I put the ball through the pipes. We have just like that built. Now I'm addicted to this game. Now I'm not going to be able to stop playing. Which for the record, let's lose right there. Uh games are a lot more addicting when you build them yourself. That's kind of the cool part about this is when you build the game yourself, it's a lot more fun to play. When you play other people's games, not as fun. When you build yourself, something special about that. Really cool feeling about that. We have a full working flappy bird game. What did we do? We built a new React application. We had the AI build the code for us. Had a bunch of issues. We worked with the AI to fix it. We basically had an AI developer working for us doing the code we need. Uh, pretty incredible. But now, let's make some alterations. Let's change let's customize this a little bit. Let's make it a little bit more fun, shall we? So, these are different things you can do, right? Like now you can go back now that your game's made and you can customize this. We have a basic flappy bird game. But what if we want to do other things here, right? What if we want to make a flappy lizard? Make the bird a lizard. Put that in. Now the A has worked. Let's change the bird to a lizard. We'll update the bird component to use a lizard emoji instead. Here's the change. Okay, there we go. It's going to change uh bird.js to a lizard. Let's do that. Let's move it back here. Boom. It's a lizard emoji. Now we got the flappy lizard. We got flying lizards. How amazing is that? Okay, now what if we want to Let's do this. Let's make it so Maybe we want to make the game more difficult. Let's go back in. Maybe this is a little too easy for us. Make the pipes move double the speed and make the pipes red. Now we're customizing the game. We're making a little bit more difficult. We're making the pipes red. What I want to do here and show for you is that now you can go back and iterate and make this game however you want to make it. If you want to add more birds, more pipes, make it more difficult, add more characters, add a story, change the scoring system. These are all things you can do. Okay, so it went in. Let's double the pipe speed. It doubled the pipe speed here and it changed the background to red. Perfect. Let's do it. Let's accept it. Let's move back here. Let's see what we got. All right, now the pipes are moving double speed and the pipes are red, right? We're customizing this game. Maybe we want to go back and change the scoring system. Whatever it is, uh, you have now built your own game. How incredible is that? You started this not knowing how to program a goddamn thing in your life. You came in here, you have your own game you built out. If you found this helpful, make sure you subscribe down below. Make sure you turn on the bell icon. Uh, make sure you hit like on the video. Uh, I'd also recommend following my ex, which is linked down below. I also have a free newsletter you can sign up for. I talk about AI in it. I talk about growing on social media. I talk about building your own business. That's all linked down below. Really hope this was helpful. I'll be back very soon with another video showing you how I can build more applications. Appreciate you all. Peace.
