---
title: "Claude Opus 4.8 actually blew my mind..."
video_id: "j-oiGiIEcws"
youtube_url: "https://www.youtube.com/watch?v=j-oiGiIEcws"
publish_date: "2026-05-28"
duration: "12:43"
duration_seconds: 763
view_count: 5621
author: "Alex Finn"
description: |
  Claude Opus 4.8 full tutorial and walkthrough
  
  2nd Youtube Channel:  https://youtube.com/@AlexFinnLabsOfficial
  FULL Claude Opus 4.8 bootcamp in the Vibe Coding Academy coming up: https://www.skool.com/vibe-coding-academy
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinn
  Henry Intelligent Machines (my new startup): https://meethenry.ai
  My $300k/yr AI app: https://www.creatorbuddy.io/ 
  
  Timestamps:
  0:00 Intro
  0:27 The changes
  5:28 Recommendations
  8:36 Product walkthrough

yt_tags:
  []



# AI-enriched metadata
content_type: "Framework"
primary_topic: "AI Tools"
difficulty: "Intermediate"
audience:
  - "Engineers"
  - "Product Managers"
entities:
  companies:
    - "OpenAI"
    - "Anthropic"
    - "Google"
    - "Slack"
    - "Twitter"
    - "YouTube"
  people:
    - "Elon Musk"
    - "Alex Finn"
  products:
    - "Claude"
    - "Claude Code"
    - "Make"
    - "Opus"
  models:
    - "Claude Opus"
concepts:
  []
summary:
  - "They implemented so many changes and a lot of these were hidden"
keywords:
  - "ai-agents"
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "claude-code"
  - "coding"
  - "frameworks"
  - "google"
  - "make"
  - "openai"
  - "opus"
  - "product-management"
  - "slack"
  - "tutorials"
  - "twitter"
  - "workflows"
  - "youtube"
---

# Claude Opus 4.8 actually blew my mind...

Opus 48 is out and it's an absolute smash home run. They implemented so many changes and a lot of these were hidden. They weren't even in the announcement. In this video, we're going to go over every single one of those changes. I'll tell you exactly what you need to do to take advantage of all these changes and then we'll even run some fun tests with it. If you stick with me until the end, you are going to be a master of the most powerful technology that's out there right now. Claude Opus 4.8. Let's go. Here we go. We are not a channel where we sit here for 20 minutes reading blog posts. Let's quickly go through all the changes, then we'll get straight into the product. First things you need to know, it smashes all the benchmarks. It beats Chad GBT55 and all the other models in all the benchmarks. Google's not even close. No one else is even close. This destroyed all the benchmarks. I actually believe this is a kind of watered down version of Mythos. I'll go into that in a little bit. I'll go in a little bit, but I actually believe this is Mythos, but kind of a little bit weaker. It's the same cost. This is mind-blowing. And I think this is a result of all the compute Elon Musk just gave to Claude, but it is the same cost as Opus 47, which is this is the first release in quite a bit of time where the price didn't go up. For both OpenAI and Enthropic, all of their new releases, the price ticked up slowly and slowly and slowly. This is the first one in a while where the cost did not go up which again just a few weeks ago Elon sold to Anthropic tens of billions of dollars of compute. I think that is a direct result of that deal which is really amazing. Here's a big one and also a big reason I think Elon's helped out Anthropic a lot. Their fast mode is cheaper. A big reason I have been using Chad GPT55 inside codec more the last couple weeks is their fast mode is dirt cheap. You get way better performance for not that much more money. Claude, their fast mode was six times more expensive which is untenable. Their limits were already low. So their fast mode wasn't worth it. Now, their fast mode is three times cheaper than it was before, which if we do the advanced algebra here, comes out to just two times more expensive than the regular mode, if my math is correct there. So, there's/fast mode is actually affordable if you're on the $200 plan. And we'll go into exact recommendations right after this, so stick around. Beats Chad GBT55. I thought 55 was the first model ever that beat Opus at coding, but this one came right back and beat it. Four times less hallucinations. So, this is a big one and this is a big reason why I think this is actually just mythos but watered down a little bit is this is one of the things they showed off with mythos was the reduction in hallucinations about four times reduction. It's matching mythos and a lot of things they advertise it for. For those who are new to the channel, kind of new to the AI world, Mythos is this model that Claude has been advertising now for a couple months. They've been advertising as some sort of doomsday model that's outrageously good that can hack any website. They've been teasing us a bit. It appears we're getting closer and closer. One big thing to notice also in their announcement blog post, this wasn't in the tweet as well, they expect to bring Mythos class models to all the customers in coming weeks, which means they're doing it. They're actually going to release Mythos again. I think Elon Musk saved Anthropic from the dead here. They were starting to lose in every single facet because their lack of compute, and now they're going to release Mythos. I don't think it's any coincidence that they're increasing limits, making prices cheaper, and releasing super powerful models within weeks of buying tens of billions of dollars of compute from Elon Musk. Now, from a new functionality perspective, here's the two big things, and we're going to demo this. when we get into the product dynamic workflows and ultra code. What are these two things? Why are they so big and important? Dynamic workflows is now Claude Code's ability to tackle months of work in just a day. What does that mean? If you give Opus48 a very complex task, a big juicy, meaty, girthy complex task, it will now spin up between tens to thousands of sub agents to tackle that task. Say you were trying to implement a really big new feature or oneshot a big app. Before, if you gave it to Opus, it would just have one agent go there and add some code, take some code away, add some code, do some research, add some code. Now, it's going to take literally thousands of those agents, send them out. They're all going to be touching different pieces of your codebase, doing research, testing things out, and simultaneously, these tens of thousands of agents are going to be writing code, testing, using the app, doing regression tests, a whole bunch of things. It's going to be really really powerful and that is now in Opus 48. Again, this is going to allow you to do months of work in just one afternoon. And then you have ultraode mode which is basically giving the keys of the kingdom to Claude code to Opus4 and saying, "Hey, use dynamic workflows whenever you want." This is only you're only using this if you got that $200 a month plan. So, this is Opus 48. I'm going to go into my exact recommendations of how to use it in a second. Then we'll go into the product and demo it out. But again, absolutely massive changes here. Let's go in the recommendations. Number one, switch all tasks to Opus 48. There's no reason not to. There's no reason not to go into Claude Code right now, pull it open, and choose Opus 48. Now, you can choose the million context if you want. I find the million context, you don't absolutely have to use it. I find once you start to fill up that million context window, the performance actually degrades a good amount. So, I'm actually an Opus 48, which is the regular context type of guy. From a effort perspective, I'm recommending doing a high by default. And then when you are building out much bigger things, switching to extra or max. But I would by default stay in high and then only switch to extra and max when you have to. Despite the fact that Papa Elon allowed Anthropic to have much more compute and capacity, it's still not as high capacity as Chad GBT. So I'm sticking with high for default, then do an extra and max if necessary. When it comes to Hermes and Open Claw, I wouldn't move it to Opus 48 just yet. This is a big mistake a lot of people make is they try to force their agents into using the latest version opus the moment it comes out. The issue is this invariably leads to errors leads to crashes and errors and crashes in openclaw and hermes are not the most fun to solve. I would wait until the official releases which typically come within 24 hours of the release of the model. So once it officially releases then you switch it over and you'll have way less crashes and and way less bad reliability. As for the slashfast mode and the new ultra code mode, I'm only using those if you're on the $200 a month plan. And even if you're on the $200 a month plan, I don't know if I'm using it for every single prompt. Like Chad GBT codeex, I'm using fast mode for literally everything cuz they give you so much capacity. Claude, their limits still aren't as high as Chad GBT. So for me, I actually have extra usage on which means once I get past limits, I just pay through the API. So, I'm actually going to be using fast and ultra code for almost everything. But for you, if you don't have the extra capacity or if you're on a $200 month plan, then I wouldn't use these modes. Totally up to you. And here's the last recommendation before we get into the products and we do some cool demos. You need to lock the hell in. You need to lock the hell in. I've been working with a lot of people lately, watching how they vibe code, seeing what they do. One issue I'm seeing is AI is enabling a lot of people to get wildly distracted. They will send a prompt to their AI and then they will go and doom scroll for an hour despite the fact that their AI finished the task like 50 minutes earlier. You cannot get distracted. If you can get into a flow state and lock the f in, you are going to get so much more done. I truly believe the number one indicator of how successful someone will be in 2026 is their level of focus. Do not allow this extra power to mean you can slack off more. Use this extra power to get more done. So really work on your focus. Put the phone away. Close social media. Close Twitter. Close YouTube and just lock in and you'll get so much more out of this tech. Now let's jump into the product and build some cool things out. I'm using Claude Code Desktop. You can use the CLI or the extension to take advantage of Opus 48. Right now, I'm going to run one of the world famous Alex Finn benchmarks on this model. This is a benchmark I've ran on every single model. Up until now, Opus 47's actually been king with by far the best scores in all four of these tests. We're going to run the 3D firstperson shooter test here. See how it does. See how it compares to the other models. If you want to run this benchmark yourself, I'll put the uh prompt for this down below so you can run your own world famous Alex Finn benchmark. I'm going to hit enter on this and I'm going to send it off and we're going to see how it does. Basically, what we're going to have it do is we're giving it creative freedom. We're saying build a 3D firstperson shooter using 3JS. Do whatever you want. Make it as creative as humanly possible. Add power-ups. Do whatever you want. We'll see how good Opus does here. Side note, remote control is active. I There's actually a setting in Claude Code not many people know about. You should be using the setting. It turns remote control on by default for every single chat. What this allows you to do is whenever you spin up a new chat in Claude, you can actually go on your phone, go into the code section in the top left, and as you can see here, that chat I just started is now on the screen. Create the stylistic 3D firstperson shooter. So, I can now go mobile whenever I want with every single chat I start. So, make sure to turn that on. A little tip for you there. Little bonus tip, go in the settings, turn on remote controls active. The only thing I ask for for that tip is you tip me with a like down below. Subscribe if you learned anything so far. Turn on notifications. And I'm going to do a full boot camp on Opus 48 tomorrow in the Vibe Coding Academy. Make sure to join that number one AI community on planet Earth. Link down below. Best decision you'll ever make in your entire life. All right, looks like it's done. It even tested itself, which is sick. Let's see how this is. Neon Assault. It's always neon themed. I have no idea why. First model that makes a non-neonthemed game. I'm going to give it a 10 out of 10. Here we go. Let's engage. This is nice. This is nice. These graphics are very, very nice. Much better. I mean, if you're this is your first time watching my channel, you might think, "What the hell is this guy talking about? This sucks. This isn't Cyberpunk 2027." But if you compare this to the default apps that previous models have built, this is pretty nice with from the walls to the ground. These are the enemies. Oh, to the way the gun shoots, to the way you can see hit markers on the enemies. I assume these are even the power-ups look nicer. Wave two. So, they got combos. They got waves. This is for sure an upgrade and probably the best version of this we have seen yet. Oh, this is an enemy. Okay, this is probably a step above what 47 gave to me. Probably just a small step. So, I'm going to give it a 9.1. I'm going to run the next three benchmarks probably on a live stream the next week. If you want to see that, make sure to turn on notifications down below for that. Again, here's a reminder of my recommendations. You want to be jumping on this now. When they release new technology, you have a distinct advantage if you start using it right away. Your competition probably isn't using Opus 48. They're probably not using the dynamic mode that sends out tens of thousands of sub agents. They're probably not using that. If you go and you use this tech and you build out really really cool things, you are going to have a distinct advantage over the rest of the field. So you want to make sure today carve off some time in your calendar. Go on do not disturb mode. Close out all the doom scrolls you got, the tickity talks, the Twitters, all of that and lock in and use this and build cool things because you have an advantage right now over everyone else if you take advantage of all these different features and functionality they just released. Let me know what you want next about Claw. Do you want tutorials and how to build really complex apps? You want deep dives into functionality? Do you want more benchmarking to see if it's the best? Let me know down in the comments. I'm super curious what you want. All my videos are based on your feedback. I hope this was helpful.
