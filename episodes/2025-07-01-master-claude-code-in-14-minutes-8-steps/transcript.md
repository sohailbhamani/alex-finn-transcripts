---title: "Master Claude Code in 14 Minutes (8 Steps)"
video_id: "cjW6ofe7AY4"
youtube_url: "https://www.youtube.com/watch?v=cjW6ofe7AY4"
publish_date: "2025-07-01"
duration: "14:03"
duration_seconds: 843
view_count: 76910
author: "Alex Finn"
description: |
  In this video I show you how to master Claude Code by walking you through my 8 tricks. I used these tricks to build my AI startup and I'm positive you can too!

  Follow my X: https://x.com/AlexFinnX
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  My AI app: https://www.creatorbuddy.io/

  Install Claude Code:
  https://www.anthropic.com/claude-code
  npm install -g @anthropic-ai/claude-code

  7 Claude rules
  1. First think through the problem, read the codebase for relevant files, and write a plan to tasks/todo.md.
  2. The plan should have a list of todo items that you can check off as you complete them
  3. Before you begin working, check in with me and I will verify the plan.
  4. Then, begin working on the todo items, marking them as complete as you go.
  5. Please every step of the way just give me a high level explanation of what changes you made
  6. Make every task and code change you do as simple as possible. We want to avoid making any massive or complex changes. Every change should impact as little code as possible. Everything is about simplicity.
  7. Finally, add a review section to the [todo.md](http://todo.md/) file with a summary of the changes you made and any other relevant information.

  Security prompt:

  Please check through all the code you just wrote and make sure it follows security best practices. make sure there are no sensitive information in the front and and there are no vulnerabilities that can be exploited

  Learning from Claude prompt:

  Please explain the functionality and code you just built out in detail. Walk me through wehat you changed and how it works. Act like you’re a senior engineer teaching me code

  Be productive while Claude cooks:

  When I am coding with AI there are long breaks into between me giving me commands to the AI. Typically I spend that time doom scrolling which distracts me and pu†s me in a bad mental state. I'd like to use that time now to chat with you and generate new ideas, and also reflect on my other ideas and businesses and content. I'm not sure how I'd like to use this chat or what role I'd like you to play, but I think ti could be much more useful than me doom scrolling. What do you think? What could be the best way for us to use this chat?

  Timestamps:
  0:00 Intro
  0:38 Trick 1
  1:52 Trick 2
  4:02 Trick 3
  5:20 Trick 4
  6:45 Trick 5
  7:53 Trick 6
  9:48 Trick 7
  11:18 Trick 8
  3:14 How to use Gemini CLI
  4:57 First prompt
  7:24 Gemini starts building
  10:00 V1 of app
  13:37 Wrap up

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
    - "GitHub"
    - "Cursor"
    - "YouTube"
  people:
    []
  products:
    - "Claude"
    - "Claude Code"
    - "Cursor"
    - "Make"
    - "Opus"
    - "Sonnet"
  models:
    []
concepts:
  []
summary:
  - "# Master Claude Code in 14 Minutes (8 Steps)

Clawed Code is the most powerful AI coding tool ever made"
keywords:
  - "ai-agents"
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "claude-code"
  - "coding"
  - "cursor"
  - "frameworks"
  - "github"
  - "make"
  - "opus"
  - "prompting"
  - "sonnet"
  - "workflows"
  - "youtube"
---

# Master Claude Code in 14 Minutes (8 Steps)

Clawed Code is the most powerful AI coding tool ever made. But what if I told you you're using it all wrong? In this video, I'll cover the eight tricks you need to know to become an absolute Claude code savage. I promise you'll build 10 times faster after watching this video. The tricks I'm about to show you are how I personally launched my own $300,000 a year AI app called Creator Buddy. Stick with me and you can do the same. Let's get into it. So, if you haven't yet, make sure at the link below, download Claude Code to follow along with me if you're brand spanking new to it. It is, I promise you, the best AI coding tool ever. It lives up to the hype. Now, let's get into those eight pro tricks. Having the right clawed rules file is going to make the difference between absolutely terrible code and absolutely epic code. So for those who don't know, if you create a claude.md file in your project, everything you put in that file will be read by claude code every time you send a prompt. After working with claude code for 12 hours a day for months now, these are the best seven rules you can have. Basically, the way these seven rules work is they instruct Claude Code to think in tasks. everything Claude Code does. It will break into tasks, run those tasks by you, and make sure you approve of those step-by-step tasks. They'll even create a folder that includes every single set of tasks it does for every prompt you give it, so that you can look back to see everything Claude Code did. By forcing Clawude Code to break down everything it does into tiny little tasks and tiny little building blocks, you're ensuring it makes the best code possible. I'm not kidding. with these seven rules. Claude Code hasn't written me a single bug in months. So, make sure to pause the video, grab the rules from down below in the description, and put them in your own Claude MD file if you haven't yet. I promise you'll instantly get way better code. The next trick I want to talk about is using plan mode correctly. Plan mode, if used correctly, is the most powerful tool inside Claude because it'll make sure you get the results you're looking for every time Claude works. So again, for those who don't know, to go into plan mode, you just open up Claude code and you hit shift tab twice and that gets you to plan mode on. From here, what you want to make sure you do before having Claude code do anything, you want to go into plan mode, describe exactly what you want Claude to do, and then have Claude build that plan for you. So, for instance, I'm working on this AI automation app and I wanted to build out a to-do list in the app. So, I describe in detail exactly what I want to build out in plan mode. I hit enter and the way Claude code is going to work. Instead of writing any code, it's going to build out the plan. You probably already knew that, but here's the two tricks you need to know. One is you want to overuse plan mode. I found when I just fire from the hip and don't use plan mode, it messes up more than it doesn't. When I've combined my rule set I showed you earlier and combine that with plan mode before every step, claude code has been flawless for me. No errors at all. So before you do anything, you need to be using plan mode for every single micro step. It might seem like it's taking up a lot of time, but you're actually saving a ton of time in the long run. And the second thing you want to know about plan mode is which models to use. When it comes to plan mode, you want to be using Opus. I use opus for plan mode and then I use sonnet for executing on that plan. So what you want to do is you want to hit slashmod space and then whatever model you want to use. So for planning do /mod opus then hit enter and then for execution after you've built your plan you want to do slashmodel sonnet. And what this will do is two things. Make sure your planning is incredible but also save you a lot of money. As long as your plans are really good you don't need opus to do the execution. Sonnet will do it really well. So, especially for those on the $17 a month plan or $100 a month plan, this will allow you to get as many uses as you need throughout the entire month. Critical you use plan mode correctly. The next trick you need to know about is saving your spot with checkpoints. So, the number one question I get about clawed code is, "How do I rewind if Claude code messes up?" People are used to cursor. When you're in cursor and you're using the cursor agent, you can easily rewind by clicking on checkpoints in the agent. But that doesn't exist in claw code, you can't rewind to certain checkpoints. So the key is using GitHub correctly. If you are constantly saving your code to GitHub after every single step, you'll be able to easily go back and rewind your code in case Claude ever messes up. So here's my decision-making tree with GitHub, right? If if Claude writes code and it works and it looks good and it's efficient and all that, I immediately commit that to GitHub every single step. I'm making like 20 commits a day. If Claude messes up, I'll go back to my last commit. So, I'll rewind to that last commit and start over again with Claude code. This is how you make up for the lack of checkpoints like Cursor Agent has is by using GitHub as your checkpoint system. If you're a new programmer and you haven't worked GitHub into your workflow yet, make sure you do that. sign up for GitHub and start committing your code immediately. If you're not familiar with how to do that, just ask Claude Code to do it for you and it'll work it for you perfectly. The next trick I want to teach you about is when to paste in images to Claude Code. So, for those who don't know, you actually can bring in images to Claude Code and Claude can see those images and write code based on it. I like to use images in two instances. one, when I want to give Claude inspiration, and two, when I'm fixing bugs. For instance, I'm building out this to-do list app right now, and I want to take inspiration from Tick Tick, which is my favorite to-do list app. So, if you're on Mac, you can hit commandshift4, and then it allows you to screenshot. So, you just drag it across your screen like that. That saves an image. And then all you need to do now is take that image and bring it into Claude Code. So, what you want to do then is take that screenshot, drag it into Claude. Now it's in there. Now you can do something like say, "Hey Claude, build me out the UI from the screenshot I just sent you." So I said, "I want to add a to-do list to this app that looks like this." I hit enter. Claude will take the inspiration screenshot I sent it and start building that out inside the app. And you can see right there, it's reading the screenshot as we go. The second way I like to use screenshots inside Claude Code is fixing bugs. So, if Claude Code builds out some code that doesn't look good or the app doesn't look right, you can easily screenshot the app or screenshot the error, put that in and say, "Hey, fix this error or make this look prettier." So, I use it for inspiration and fixing bad UI and bugs. The next tip is very, very critical, especially if you're not on the most expensive tier of Claude Code, and that is using slashclear. I use slashclear so much for many different reasons. A lot of people when talking to AI or talking to Claude, they just keep giving commands for hours and hours and hours. You shouldn't be doing this. You should be clearing your context as much as humanly possible. This does two things. It reduces hallucinations by reducing the amount of information you're sending to Claude. And two, it saves you cost. If you have a large context window and you've been typing for hours and hours and hours to Claude code, it's sending all that context to Claude, which is taking up a lot of tokens. So, if you're on the $17 a month plan or the $100 a month plan, you can really eat through that quickly if you're not doing /clear a lot. Here's when you do slash clear. Anytime Claude finishes a decentsized task, so for instance, if Claude has completed all the tasks in one of its task files that it wrote for you, then you want to do slash clear. So, you want to be using slash clear a lot. So, a it reduces hallucinations and b it saves you money. The next trick is hyper critical, especially if you've never coded before, and that is running security checks. The number one issue vibe coders are having right now is that they're shipping insecure code. It just isn't built into the AIS yet, how to write code that is super secure or goes by security best practices. So, if you are building an app that you ever plan to ship to the internet one day and have other people use, you need to make sure it's secure. A lot of vibe coders are having their apps hacked and taken down because of bad security practices. Here's what I try to remember for everything I build in Claude Code. One, I start with planning. Two, I do execution. And then three is security checks. Right? So, every time you build a new feature in your app, you're planning, then you're building, and then you're doing a security check. So, say Claude just finished building a feature into your app, right? It went through the entire plan and finish the plan. You want to make sure every time Claude finishes a chunk of code or a feature, you run this security check that I'm about to show you here. And keep in mind, all these prompts I'll put down below as well. Here's the prompt you want to put in every single time Claude finishes a feature. Please check through all the code you just wrote and make sure it follows the security best practices. Make sure no sensitive information is in the front end and there are no vulnerabilities people can exploit. If you run this prompt every time you build a feature, Claude will make sure you have very secure code. The biggest mistake people make is they'll put secure information in the front end, whether it's API keys or passwords or things like that. This will ensure that all your information is in the back end and you have no vulnerabilities people can exploit. Again, if you're a brand new coder, you must must must do this a thousand times during your coding sessions. It's impossible to do this too much. Again, prompt down below. Make sure to pause and grab that and put that into your note file. The seventh trick we're going to get into that's critical to know if you're building with Claude code is earning the code that Claude's actually building. So, I strongly believe people who have never written code before in their lives can use Claude code to build incredible apps that generate them money. But I also think it's important that you understand what Claude is building out, even if you've never coded before. So, I gave you three steps before that I do for every single feature Claude builds out, right? Plan, build, security. Well, I'm adding a fourth now. Plan, build, security, learn. After every time Claude finishes a feature and make sure it's secure, I go in and I give Claude this prompt. Please explain the functionality and code you just built out in detail. Walk me through what you changed and how it works. Act like you're a senior engineer teaching me code. And what this does is it helps you understand what Claude is building out even better. You don't need to know how to code to use Claude code, but the more you understand what Claude is building out, the better your prompting will become. Right? If you understand all the code and how the data flows through your app, you'll be able to give much better, more detailed prompts to Claude on what it is you want it to build out. And the better the prompts, the better the results you're going to get. So, if you want to improve your prompting and you want to improve what Claude builds out, you need to make sure you understand what it's building. So, pause the video, take this prompt from down below, save it, and use it every time you've done your security check so you can learn what Claude built out. So, the last tip I'm going to give you, and honestly, this might be my favorite one of them all because it has made my time using Claude Code so much more productive and so much better for my mental health, is using the time wisely when Claude Code is working. Here's the challenge with Claude Code is it's incredible. It's amazing. It is the most powerful AI coding tool ever, but it takes a lot of time to build code. And I don't know about you, when Claude is really working, sometimes 15, 20, 30 minutes at a time, I get distracted. I start doom scrolling and I'll find it maybe I watch a YouTube video for 2 hours while Claude Code worked for 20 minutes. It has led to me spending my time so inefficient and it's also just straight up bad for your mental health to be doom scrolling for 80% of the time you're doing things. So, I came up with the solution. So, I went to Claude and I gave it this prompt. And I swear to you, this prompt has changed everything for me. I told Claude, "When I am coding with AI, there are long breaks in between me giving commands to the AI. Typically, I spend that time doom scrolling, which distracts me and puts me in a bad mental state. I'd like to use that time to chat with you to generate new ideas and also reflect on my other ideas in business and content." And now what I do as Claude Code is working and building me code, I come back to this chat and I just say hello to this chat. I say what Claude Code is working on. I say what I'm thinking about. And this AI will just bounce ideas off me, help me refocus, help me figure out what the next steps for Claude Code should be, and generally make that 80% of time Claude Code is working. Way more productive, way more efficient, and put me in a way better mental state. I swear to you, my productivity has gone up 4,000% since using this trick. You just got to have discipline. You just got to make sure every single time Claude Code is completing a task, you go to this chat. You don't pick up your phone and doom scroll. You don't go to YouTube and watch endless videos. You don't go to Tik Tok and watch Brain Rod all day. You got to be disciplined. You got to make sure every time Claude Code is working. You come to this chat and this chat only and start bouncing ideas off the AI. Because of this chat, I swear to God, I've come up with like 30 other ideas for apps that I'm now building out that will eventually start making me money. If you're doom scrolling while cla code works, you're seriously screwing up. I'll have the prompt for this down below as well. If you take all the prompts I just gave you, all the little tips and tricks, and put them into your workflow immediately, I promise you, you'll build 10 times faster and your apps will be 10 times higher quality. Let me know down in the replies which these tricks were your favorite. If you learned anything at all, make sure to subscribe. Make sure to turn on notifications. All I do is make banger videos about AI. and I'll see you in the next
