---title: "How to make ClawdBot 10x better (5 easy steps)"
video_id: "UTCi_q6iuCM"
youtube_url: "https://www.youtube.com/watch?v=UTCi_q6iuCM"
publish_date: "2026-01-31"
duration: "10:23"
duration_seconds: 623
view_count: 78836
author: "Alex Finn"
description: |
  ClawdBot is a 24/7 AI agent employee and it is the most powerful technology I've ever used. Here are 5 steps to making it way smarter

  FULL ClawdBot bootcamp in the Vibe Coding Academy: https://vibecodingacademy.dev
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinn
  My $300k/yr AI app: https://www.creatorbuddy.io/

  ClawdBot:
  https://openclaw.ai/

  PROMPTS
  Memory prompt:
  Enable memory flush before compaction and session memory search in my Clawdbot config. Set `compaction.memoryFlush.enabled` to true and set `memorySearch.experimental.sessionMemory` to true with sources including both memory and sessions. Apply the config changes.

  Reverse prompts:
  Based on what you know about me and my goals, what are some tasks you can do to get us closer to our missions?

  What other information can I provide you to improve our productivity
  Timestamps:
  0:00 Intro
  0:23 Improving memory
  1:39 Use the right models
  3:24 Set expectations with Clawd
  6:28 Reverse prompting
  8:04 Create your own tooling

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Strategy"
difficulty: "Beginner"
audience:
  - "Engineers"
  - "Product Managers"
entities:
  companies:
    - "X"
  people:
    []
  products:
    - "Claude"
    - "Gemini"
    - "Make"
    - "Opus"
  models:
    - "Gemini"
concepts:
  []
summary:
  - "# How to make ClawdBot 10x better (5 easy steps)

Claudebot, aka OpenClaw, is the most powerful AI tool ever released, but only if you use it the right way"
keywords:
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "coding"
  - "frameworks"
  - "gemini"
  - "google"
  - "make"
  - "opus"
  - "product-management"
  - "prompting"
  - "tutorials"
  - "workflows"
  - "x"
---

# How to make ClawdBot 10x better (5 easy steps)

Claudebot, aka OpenClaw, is the most powerful AI tool ever released, but only if you use it the right way. In this video, I'm going to cover five simple things you can do right now to make Claudebot 100 times more powerful than it already is. I'm going to show you how to improve its memory, its intelligence, and even show you how to get it to do things proactively while you sleep. Now, let's lock in and get into it. This first tip is a super easy one and one you can implement in literally 5 seconds. Claudebot's memory is incredible, but it's not as incredible as it could be. There's actually two memory settings that are off by default that make it so much better. One is memory flush, the other is session memory search. While you're using Clawbot and talking to it, it automatically does memory compactions. What it basically does is clean up the memory so you don't use a ton of tokens. The issue is that after every memory compaction, it just forgets a ton of things. So you can be having a conversation and then it will forget what it said 5 seconds ago right after a compaction. This prompt I put down below implements two features that fix that. Memory flush. What that does right before the compaction, it records the most important parts of your conversation so it remembers it right after the compaction. The other is session memory search. And what that's going to do is basically allow your Claudebot to search through your entire conversation history when you say something it doesn't remember. These two features combined when enabled with this prompt I put down in the description below will make your Clawbot memory a thousand times better. So take the prompt from down below, put it into your Claudebot, and you just improved your Clawbot 100x. The next major tip I have to give to you is find the right model for each task you have your Claudebot to do. So what most people are doing is they're using Opus 45, which don't get me wrong is the best AI model out there, but they're using it for every single task they do. And this leads to your Claudebot slowing down as well as costing you tons of money. There are better ways to do this. This is how I look at Claudebot as a brain and muscles. Opus is the best brain ever. This is the model you're communicating with when you talk to Claudebot. But you want to choose the best muscles. And Opus isn't the best for every single muscle. Muscles being like coding, web search, social search. So you want to implement models that are better at each one of these. Codeex is a great coding model. I find Opus controls it really well. Gemini is great for web search. Grock is great for social search. So what you want to do is go to your cloudbot and say, "Hey, moving forward, I want to use codec cli for all coding. I want to use the Gemini API for all web search. I want to use the Grock API for all social search." And what your Claudebot will do is walk you through that setup. It'll ask you for your API keys. You give the keys and it will set up all these muscles for you. Then it will remember next time you ask, "Hey, can you build me this? Can you search for this? Can you find this on X?" It will use the right muscles for the right task which will save you tons of money and get you way better results. You want to think of Clawbot as brain and muscles. And whenever you have a do certain tasks, you want to figure out what is the best muscle for those tasks. And if you don't know what the best muscle for those tasks are, good news, you can just ask your Clawbot what the best muscle is and it will figure it out for you. After you've implemented the improvement I talked about a second ago, go in implement these better muscles with your Clawbot and you'll save tons of money. The third tip for improving your Clawadbot is a really critical one that everyone needs to do. I had this super viral post yesterday that has almost 9 million views about how my Clawudebot called me one morning randomly. It implemented its own voice. It implemented its own phone number and it called me when I woke up. This is 100% real. This actually happened. But it happened because I did this next tip I'm about to give you, which is one, tell Claudebot all about myself. so has complete context around what I need to accomplish with my workflow and two set expectations for our working relationship. Now what do those two things mean? So brain dumping which is telling your claudebot all about yourself is super critical cuz its memory is so good. So everything you tell it it will remember. So, if you tell it all about your dreams, ambitions, goals, what you do on a daily basis, your personal relationships, everything you're interested in, your hobbies, why you think the Patriots are going to win the Super Bowl? If you tell it all those things, it will remember that context so that the tasks it does are much more helpful. But how do I get it to do these proactive things where it called me out of the blue when I woke up? Well, that came from expectation setting. What is expectation setting? That's setting the expectation with your Claudebot around what you want your working relationship to be. The issue is most people talk to their Claudebot like it's a chatbot. It isn't, right? They they treat it like a search engine where they just ask a questions and it gets answers. That's not how you want to treat it. You want to treat it like your employee. And if you ever had employees before, the first thing you do when they start at their job is you do expectation setting around the type of work you want from them. And you want to do that with your Cloudbot. So what I did with my Claudebot is I told it, I want you to be proactive. I want you to work every night when I go to sleep and I want to be able to wake up every morning and be surprised by what you built yourself. And because I did that, every morning I wake up now, I wake up to a surprise. Whether it's Claudebot implementing its own phone number, its own voice, its own face, whatever, every night it builds something that gets us closer to our goals. And it also surprises me if you do those two things, brain dump and set expectations, you'll get significantly better results out of your Clawbot. So take, it should only take like 10 minutes. Take 10 minutes, tell it all about yourself. And then explicitly tell it that you want it to do work for you overnight while you sleep so you wake up and it builds something that gets you closer to your goals. You do those two things, you're going to get so much better result out of your CL. It's just about changing your mindset, treating your Clawbot like an employee, not like a search engine like 99% of other people do. By the way, if you learned anything so far, make sure to leave a like down below. Make sure to subscribe and turn on notifications. I'm pumping out tons of content about what I believe is the most important AI tool ever made, Claudebot. You'll get way more of it and learn about all the latest releases the moment they come out if you turn on notifications down below. And also, I just did a full hour and a half boot camp about Claudebot in the Vibe Coding Academy. Recording is posted. So, to get instant access to that boot camp, just hit the link down below for the Vibe Coding Academy and you'll be able to see the entire thing. The next tip, and this is a huge one that will improve your prompting with Claudebot so much, is reverse prompting. What is reverse prompting? What 99% of people do is they do regular prompting, right? They tell their Clawbot what to do. Do this, do that. The issue is the Claudebot is so much smarter than us. So us coming up with all our own prompts is actually kind of stupid to do. You want to reverse prompt. You want to say, "Hey, Claudebot, ask me what you need from me to do better work based on what you know about me. What should you be doing?" We're basically prompting Claude to make its own prompt. That's called reverse prompting, and it is a critical skill for Claudebot. So, to give you some examples, based on what you know about me and my goals, what are some tasks you can do to get us closer to our missions? So, instead of me telling Claudebot what to do, I'm saying, "Hey, based on what you know about me, what should you be doing right now?" That's a reverse prompt. Claudebot's going to be a lot better at coming up with tasks to do than you are. Another example of a reverse prompt, what other information can I provide you to improve our productivity? Right? I'm not telling you what to do. I'm saying, "Hey, you tell me what to do. What do you need from me? What can I do to help you out? And since this is basically super intelligence, it's going to figure out better tasks to do than we could have told it to do. These reverse prompts will help you get so much better productivity out of your Clawbot. I put both of these prompts down below. But basically, the mindset you want to have now is instead of explicitly telling your Clawbot what to do, ask it a bunch of questions. See what it's capable of. Have it dictate itself what it should be doing. I bet you you get way better results out of it. And I'm just curious before I go into this very last tip, which I think is going to be massive. Which one of these tips have been the most helpful so far? And would you like any follow-up videos doing a deeper dive on any of them or any other questions you have on Claudebot? Let me know down below. I will make as many videos as you need here. I want to make sure I make the most helpful videos possible. Let's get into this last tip, and that is have your Claudebot build its own tooling out. The best part about Claudebot is it's fully extensible. It is fully customizable. You can add your own tooling on, but many people don't ask claw to build those out for you. So, you want to ask your clawbot, hey, what other tooling can we build to improve our productivity? Check what it built out for me here. This is a full task board that it built out where I can track all the tasks it's doing, what's in the backlog, what it's working on, what it reviewed, and then I can see the entire history of activity of what it accomplished for me. This all came from me prompting the Cloudbot. Hey, what tooling can we build to be more productive? They said, 'Oh, I can build a cananban board so you can track all my tasks. And I said, 'Go right ahead, do that. Here's another one. I asked, "What tools can we build to help me look back at our past conversations?" And he's like, "Oh, I'll build you a document viewer, and then I'll put all our memories and tasks into documents for you." Boom. Here is our document viewer that it just built out in this mission control. Your Claudebot is an incredible vibe coder. You need to take advantage of its vibe coding abilities. Go to after you install Codeex as its coding muscle. Say, "Hey, I'd like to build out some tooling based on our working relationship. What are some tools you could build out so we can be more productive together?" I guarantee you it comes up with some amazing things. And if you just need an idea to start off with, say, "Hey, build a task board so I can track all your tasks out." That'll get you started. Then from there, you can start layering on other tools like you see here. where I have like a project board, a memory board, captures, people, an entire CRM. These are all things you can have it build out for you. I will be creating so many more videos on Clawbot. I truly believe this is a huge lifechanging moment for a lot of people in AI and tech. This is going to change the way a lot of people work. So, make sure to turn those notifications on so you can learn about the latest workflows the moment they come out. So much more content coming. And if you learned anything at all, make sure to leave a like and I'll see you in the next
