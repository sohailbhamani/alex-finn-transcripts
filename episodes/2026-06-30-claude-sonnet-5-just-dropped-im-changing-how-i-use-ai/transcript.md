---
title: "Claude Sonnet 5 just dropped. I'm changing how I use AI..."
video_id: "uU0RFxGv-Ks"
youtube_url: "https://www.youtube.com/watch?v=uU0RFxGv-Ks"
publish_date: "2026-06-30"
duration: "11:56"
duration_seconds: 716
view_count: 1935
author: "Alex Finn"
description: |
  A complete walkthrough of the new Claude Sonnet 5 release
  
  FULL Claude Code bootcamp in the Vibe Coding Academy coming up: https://www.skool.com/vibe-coding-academy
  2nd Youtube Channel:  https://youtube.com/@AlexFinnLabsOfficial
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinn
  Henry Intelligent Machines (my new startup): https://meethenry.ai
  My $300k/yr AI app: https://www.creatorbuddy.io/
  
  Timestamps:
  0:00 Intro
  0:41 What Sonnet 5 is
  3:41 Performance test
  6:25 Sonnet 5 best practices
  10:15 Fable 5

yt_tags:
  []


# AI-enriched metadata
content_type: "Framework"
primary_topic: "AI Tools"
difficulty: "Intermediate"
audience:
  - "Engineers"
  - "Executives"
  - "Product Managers"
entities:
  companies:
    - "Anthropic"
    - "Notion"
  people:
    []
  products:
    - "Claude"
    - "Claude Code"
    - "Notion AI"
    - "Make"
    - "Opus"
    - "Sonnet"
    - "Computer Use"
  models:
    - "Claude Sonnet"
concepts:
  - "Tell you how you should be using it now, should you be using it in hermes, should you be using open claw, should you be using it in claude code, and where you shouldn't even be touching it at all"
summary:
  - "Claude Sonnet 5 has released and it is by far the best bang for your buck in AI right now"
keywords:
  - "ai-agents"
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "claude-code"
  - "coding"
  - "computer-use"
  - "frameworks"
  - "make"
  - "notion"
  - "notion-ai"
  - "opus"
  - "prompting"
  - "sonnet"
  - "tutorials"
---

# Claude Sonnet 5 just dropped. I'm changing how I use AI...

It happens. Claude Sonnet 5 has released and it is by far the best bang for your buck in AI right now. It has almost the performance of Opus 48 but for a fraction of the price. In this video, we'll go through every single change with Sonnet 5, but more importantly tell you how you should be using it now, should you be using it in Hermes, should you be using Open Claw, should you be using it in Claude Code, and where you shouldn't even be touching it at all. I'll also give you a few tips on how you can get the absolute most out of this model immediately. And then on top of that, we'll go into what this potentially means for Claude Fable 5. Now, let's lock in and get into it. So, this is a big one. It is a full number upgrade. This isn't a 4849. No, it is Sonnet 5, a full number upgrade. And it comes with a lot of big changes. First of all, let's talk performance. One, it blows Opus 46 out of the water. I don't know if you remember, it was like a month and a half ago. Opus 46 comes out and it was really good. This lightweight, cheaper, quicker model destroys it. That is massive. And that is big because Claude has been number one when it comes to Agentic models forever. When it comes to OpenClaw and Hermes, nothing comes close. And a lot of people have been upset because you got to pay API pricing for clawed models inside Hermes. Well, now you don't need to pay as much because you can use Sonnet 5. It is almost as good as Opus 48. And I'll show you some of the numbers in a second here, so stick around for that. But it's almost as good as Opus 48, which Opus 48, I believe, is the smartest model on planet Earth right now if you don't count Fable 5. More on that later. Here's a big one. Fraction the price. Everyone in their mothers has been crying that AI has gotten too expensive lately. Everyone's been crying again about paying API prices for Claude with Hermes. With OpenClaw, fraction of the price, you're saving a ton. If you're anything like me, your usage with Hermes is out of control when you use Claude. I've spent $1,300 in the last month on Claude tokens inside Hermes. So, yeah, this is a big welcome upgrade. It is significantly faster. That is a big sticking point with Opus as well. It can get pretty slow at times. And the big upgrades come to reasoning, tool use, coding, and knowledge work. Basically, the four horsemen of agentic work. I really think this is the model Anthropic puts out to really nail open claw and Hermes use cases. This isn't your clawed code, agentic loop, infinite autonomy model. This is your you're working with Hermes. You're working with OpenClaw. You're doing basic coding tasks and it is your agent that is partnering with you. So, let's talk about the numbers real quick. Absolutely destroys Sonnet 46 on basically every single measurable benchmark there is when it comes to Opus 48. Doesn't beat it in any specific benchmark, but it comes really, really close. A little bit better on knowledge work, but computer use, everything else, it is very, very close. But again, that is amazing because you're not paying nearly as much for Sonnet 5 as you are for Opus. That's why you're now plugging this into everything you do. Now, let's look at cost versus performance. If you take a look here, for similar task, you're paying out $8 for Opus 48 on medium. Similar task, you are paying about half that price for Sonnet 5 and only getting a small 5% downgrade on the pass rate. So, you're paying about half the price for roughly a little bit worse performance than Opus 48. That's pretty good, especially if you're using any sort of agents. So, let's do this. First, we're going to do a quick performance test of Sonnet to see how it fares against Chad GBT55 and then we'll go into how to use it best. I'll show you some best practices with using it for Claude code as well as Hermes. So, I am in Claude Code Desktop. I believe this is the best way to be using Claude. A lot of people use the CLI. I like the desktop. You can monitor all your sessions really well. The user experience is really nice. You can plug in anything you want. I use linear and a whole bunch of other plugins. So, I'm using Claw Desktop. I recommend you use the same thing. If you go to the bottom right, you'll see it right there. Sonnet 5. Miss you, Fable 5. Sonnet 5. Boom. I'm going to put in a prompt I will also be giving to Chad GBT55 so we can run this test cuz I think those are two comparable models. This with Chad GBT55. This is going to build a really nice 3D boat simulator. I'm going to put the prompt down below if you want to copy it and run it yourself as well. I'm going to hit enter on that. I am also going to be putting this in codecs and giving this to just Chad GBT55 Medium. I'm going to hit send on that at the same time, but we're going to see what performs better, Chad GBT55 or Sonnet. Then I'm going to give you all those master tips on how to be getting the most out of Sonnet. All right, let's do this. Let's start with Chad GBT55. This was Chad GBT55's 3D ship simulator. In the prompt, if you take a look at it, it says allow to configure the rain, the wind, the waves. Uh, a little disappointing. One, I can't move the camera at all. Two, the ship is not moving. Three, the water is not moving. Uh, the rain actually is quite impressive to be quite honest with you. That is a lot of rain. Let's see. We go wave height. Nothing happens. Rain density. That is a lot of rain. Uh, the weather's nice. Everything else nights, not so much. Let's take a look at what Sonnet 5 did here. I like it better. The waves are moving. The ship is moving. Is there any rain going on at the moment? Know, you can kind of see thunder there, but I like the way the ship and the waves look a lot more. Let's bump up the wind. Yeah, it makes the waves Oh, yeah, the wave. Oh, the waves are crashing into that ship. Wow, the ship is going nuts. I would not want to be on that ship. This is rather impressive. It looks like it is better than 55 to be quite honest you based on this test. So, one thing to note here as well from a pricing perspective, even though I like these results better from Sonnet 5 than from Chad GPT and the UI is still way better with Claude Sonnet than Chad GBT, I don't know why Chad GBT can't figure out the UI side. I will say this, the pricing is still significantly better with Chad GPT in almost every single aspect. So if price is important to you, if you're paying for API usage for your pure coding efforts like this, I still probably lean chat. So we're back in Claude Code Desktop here. Again, what I believe is the best way to use Claude and Claude Code. Here is how you want to use Sonnet. You want to use Sonnet for all your basic coding tasks and you want to use Opus 48 in the ultra mode for a lot of your planning and really complex tasks. So for instance, I'm starting out this new project. It is a productivity app. What I'm going to do is I'm going to go into plan mode. And what I'll also do is go into Opus 48 and go into Ultra Code. Now, this is probably only safe for you if you're in the 20x max. If you're anything lower, you probably just want to go into max mode here. But if you have the 20X, you go into ultra code. This is where you're going to do the planning of the entire app. So if you're building an application, you're planning some monster functionality out, some monster app out, you go into plan mode, you go into Ultra Code. The reason why I like Ultra Code is it can spin up workflows at any time. For those who don't know, workflows is basically Claude's sub agent functionality where it spins up potentially thousands of sub aents to do work for you. So I like the Ultra Code mode. So I have a prompt to build this productivity. I have basically a notion clone. I'm going to hit enter on that in plan mode in ultra code. It is going to use tons of compute to make sure this is planned out. Well, this is the key here. When you're doing actual execution, you don't need a ton of compute. If the plan mode was done with a lot of compute, right? So, if you have a really nice detailed plan, you don't need the smartest model in the world to do the execution. So, we still use Opus 48 for the planning, but what we're going to do in a second is use Sonnet 5 for the execution of that detailed plan. So, we're going through the plan mode. It's asking a ton of great questions around, do I want it to be multiplayer? What kind of writing support does it have? Is it a writing system? Yep. We're going to give it Notion AI functionality. This is a great strategy. If you pay for any apps, just rebuild it in cla, right? You'll save tons of money. We're going to do MVP first. So it's going in, it's building the plan. And here is what I love. It is starting a workflow to design the architecture. So what you'll see here is actually spin up tons of sub aents to design the architecture. This doesn't happen with sonnet, right? So this is why you want to be doing this opus so you get the maximum compute in the important part which is the planning. Look at this. Five agents working, tons of tokens, tons of tool use. This is awesome. All right. Looks like it built out the entire plan, put it in a markdown file, which is sick. I'm going to go into Sonnet 5. And because we have such a good plan built out, we can go in do Sonnet 5 on medium. So, this can be dirt cheap. And we can say, "Okay, now execute on the plan." And Son of 5 will get to work. If we were doing Opus 48 with this, this would cost us way more money. This would be very expensive to do. But now that Sonnet 5 is past opus 46, almost 48, we can run on sonnet. will get the same quality project done for way less. This is great if you're on one of the cheaper plan models. As for Hermes Agent Open Claw, if you are watching this video shortly after I put it out, Sonnet 5 probably won't be in your directory of new models. But what you can do is go to your agent if you're already using the Claude API. Just say, "Hey, switch the Claw API to this set five string. Look it up online." and it can switch in the back end for you and you'll be good to go. You'll be on the new Sonnet 5 model. I recommend using Sonnet 5 now in your Hermes and Open Claw. Claude again makes the best models when it comes to agents. It really isn't close. Chad GBT 5.5 is usable. Claude is the goat though. The issue again very expensive. Sonnet 5 brings those cost down. I'd recommend using Sonnet 5 through the API. As for Fable 5, it looks like it is going to return soon. A bunch of strings have been found in the clawed code around Fable 5, including looking like it is going to require API usage, as well as looking like it is going to require verification. So, you're actually going to need to identity verify to make sure you're in the United States of America. If you're outside the US, I'm so sorry. If you're inside the US, prepare to give up your identity in order to use it, which is fine. I guess it is what it is. I just want the model back. I personally will be giving the identification so I can use the model. I don't do anything crazy or illegal with AI, so I really have nothing to fear. But good news, looks like Fable 5 is coming back very, very soon. The bad news is uh you're going to have to pay API pricing and you're going to have to give up your identity in order to use it. It is what it is. That is Sonnet 5. It is not replacing Opus 48 for me. It's only replacing Opus 48 for cheap and quick and easy tasks in times in which I'm looking to save money like with using OpenClaw and Hermes because I am spending thousands a month on those. This should bring down my bills by a little bit while getting me comparable performance to Opus 46. So, it is not a full replacement for Opus. It is a replacement in very strategic areas. If you learned anything at all, leave a like down below, subscribe, turn notifications. All I do is make amazing videos about AI. doing full live boot camp on Sonnet 5 this week in the Vibe Coding Academy. Link for that is down below. Is a number one community in AI on the entire internet. Make sure to join. You will learn a ton. It'll be the best time of your life. Sign up for that. Hope this was helpful. See you in the next video.
