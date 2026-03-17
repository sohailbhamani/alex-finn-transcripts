---title: "You're prompting Claude Code wrong. Here's how to do it correctly..."
video_id: "7WuKgc3-_-s"
youtube_url: "https://www.youtube.com/watch?v=7WuKgc3-_-s"
publish_date: "2026-01-03"
duration: "14:42"
duration_seconds: 882
view_count: 19541
author: "Alex Finn"
description: |
  Anthropic just released a Claude Code prompting guide. Here's the top 10 tips from it

  Join the Vibe Coding Academy waitlist: vibecodingacademy.dev
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinn
  My $300k/yr AI app: https://www.creatorbuddy.io/

  Prompting guide:
  https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-4-best-practices#research-and-information-gathering

  Load up context prompt:
  take a look at the app and architecture. Understand deeply how it works inside and out. Ask me any questions if there are things you don't understand. This will be the basis for the rest of our conversation.

  Tool use summaries:
  After completing a task that involves tool use, provide a quick summary of the work you've done

  Adjust eagerness down:
  Do not jump into implementation or change files unless clearly instructed to make changed. When the user's intent is ambiguous, default to providing information, doing research, and providing recommendations rather than taking action. Only proceed with edits, modifications, or implementations when the user explicitly requests them.

  Adjust eagerness up:
  By default, implement changes rather than only suggesting them. If the user's intent is unclear, infer the most useful likely action and proceed, using tools to discover any missing details instead of guessing. Try to infer the user's intent about whether a tool call (e.g. file edit or read) is intended or not, and act accordingly.

  Use parallel tool calls:
  If you intend to call multiple tools and there are no dependencies
  between the tool calls, make all of the independent tool calls in
  parallel. Prioritize calling tools simultaneously whenever the
  actions can be done in parallel rather than sequentially. For
  example, when reading 3 files, run 3 tool calls in parallel to read
  all 3 files into context at the same time. Maximize use of parallel
  tool calls where possible to increase speed and efficiency.
  However, if some tool calls depend on previous calls to inform
  dependent values like the parameters, do not call these tools in
  parallel and instead call them sequentially. Never use placeholders
  or guess missing parameters in tool calls.

  Reduce hallucinations:
  Never speculate about code you have not opened. If the user
  references a specific file, you MUST read the file before
  answering. Make sure to investigate and read relevant files BEFORE
  answering questions about the codebase. Never make any claims about
  code before investigating unless you are certain of the correct
  answer - give grounded and hallucination-free answers.

  Timestamps:
  0:00 Intro
  0:26 Tip 1 explain motivations
  1:43 Tip 2 context windows
  2:57 Tip 3 load up context
  4:04 Tip 4 use git
  5:18 Tip 5 tool use summaries
  6:33 Tip 6 adjust eagerness
  8:02 Tip 7 careful about the word think
  9:25 Tip 8 use vision
  11:20 Tip 9 use parallel tool calls
  12:56 Tip 10 reduce hallucinations

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Tools"
difficulty: "Intermediate"
audience:
  - "Engineers"
entities:
  companies:
    - "Anthropic"
    - "GitHub"
  people:
    []
  products:
    - "Claude"
    - "Claude Code"
    - "Make"
    - "Opus"
  models:
    - "Claude Opus"
concepts:
  - "You should be using as many images as possible with every single prompt you use"
summary:
  - "Claude Code is the most powerful AI tool in the world, but only if you use it the right way"
  - "When you start a new session or start a new chat automatically in the context, claude will understand all your recent sessions and all the past changes you made in those sessions because it can see al"
keywords:
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "claude-code"
  - "coding"
  - "github"
  - "make"
  - "opus"
  - "product-management"
  - "prompting"
  - "tutorials"
---

# You're prompting Claude Code wrong. Here's how to do it correctly...

Claude Code is the most powerful AI tool in the world, but only if you use it the right way. Anthropic just released a secret guide to prompting Claude Code. I went through the entire guide and picked out the 10 best tips that will 100x the power of Claude Code for you. This is a mustwatch video if you're using Claude Code or even thinking of using Claude Code. I really didn't know any of these before. Let's get into it. This first tip will get way better results out of cloud code and that is explaining your motivations in detail. What does that mean? So, I'm building out this project management tool here and I want to add a calendar component to this project management tool. What most people typically do is go in here and say build me a calendar tool in this and hit enter and that's it. Claude Code is spectacular at making proactive changes for you, thinking ahead of you before you even think of things. So if you give a detailed prompt on your motivation behind these changes, Claude will actually make other great changes for you at the same time. So for instance, what I would do here is I'd say build me a calendar tool on this. The idea is that all notes, tasks, and everything else we build can be stored on this calendar. And I hit enter on this. Claude Code will now not only add a calendar to our app, but it will make it so that everything we add into our project management app will be compatible with this calendar moving forward. This will make it so everything else we add will match our core motivations and make the output so much more aligned with what we actually want. So, always remember to include not only what you want Claude Code to do, but why you want to do those things inside of your prompts. The next tip Anthropic gave in their master class is do not worry quite as much about context windows. Claude Code in their most recent update a couple weeks ago added a new feature where it does auto compaction much more intelligently. That means you do not have to worry quite as much about doing slashclear or slashcompact all the time to save your context. Claude now compacts very intelligently as it goes, which means you can just use one window of Claude code and then just keep giving prompts all the way down on it without having to clear context every 5 seconds. Over the weekend, I built this site for my fantasy football league where it tracks all the statistics across all 11 fantasy seasons we've had. It has all this incredible data about players and teams and all that. I built out this entire app over the course of 3 days in like 12 hours without clearing context once. It remembered everything, all the motivations, everything I wanted in this app without having to do slashclear once. And it built out the entire app in the session, all in one single window. Slash really isn't necessary anymore. Claude Code is so good at compacting context. You can just use one window and not have to use your brain cycles on worrying about context. Which brings me to tip number three, which is don't be afraid of loading up your context with really important data the moment you start a new chat. So, say we start a new session, we come in, we want to work on this project management app. You want to load up the context right off the bat with anything that's important that you want Claude to remember for as long as you're working with it. Here's what I do with every new session. Steal this prompt from down below. Take a look at the app and architecture. Understand deeply how it works inside and out. Ask me any questions if there are things you don't understand. This will be the basis for the rest of our conversation. Now, for as long as I'm using this chat, Claude will know inside and out how our app works. If you just go in straight away and start having Claude build things, it's not going to have context around our entire app and all the architecture and all that. But if you start every new session with this prompt, you're loading the context with all the important details about your app. And it will work so much better and so much more efficiently moving forward. It's going to save you a ton of time and it's going to get you way better results. So, steal this prompt, bookmark it, and use it every time you start a new chatter session. Which brings us to tip number four, which is use GitHub a ton. The reason why you want to use GitHub a ton is if you're using Git, Claude actually has automatic access to all your commits and all your changes on your project. What this means is when you start a new session or start a new chat automatically in the context, Claude will understand all your recent sessions and all the past changes you made in those sessions because it can see all your changes inside of GitHub. So this is the fantasy football app I just built and I have a bunch of commits here and the moment I start new chat, it will know everything it added in past sessions. This is all automatically loaded in. So, if you're building an app right now with Claude Code and you're not using GitHub, make sure you go to github.com, create a new repository. It's all for free. And then tell Claude to commit the code to that repository. Now, as Claude makes changes, it will make commits to GitHub, back up your code, and it'll know every time moving forward all the changes it made in GitHub. This again is going to make Claude code so much more powerful because it will remember all its changes from the past. Use GitHub. Use it a ton. Constantly commit your code to GitHub. It'll make Claude Code better and it'll also back up your code. Which takes me to my next tip, which is a critical rule you need to put into Claude Code if you are a new user of Claude Code or new to Vibe Coding. And that is this rule right here. After completing a task that involves tool use, provide a quick summary of the work you've done. This is very important to add if you're newer because Claude Opus, as Anthropic describes in his blog post, which for the record, if you want to see the blog post, put the link down below, is the most eager model Anthropic has ever made, which means it's going to be super proactive with tool use. It's going to be super proactive of building features, writing code, and all that. And a lot of the time, it's so eager that it's not going to explain to you actually what it did after it uses different tools and does complex things. So, if you're a new vibe coder and you want to understand everything Claude is doing, which I highly recommend you do, especially if you want to be an expert on this, add this rule to your claude.md file, which I I'll put all this down below so you can just copy and paste it in. Make sure you have a claw.md file in your root here, and then paste this in after completing a task that involves two use. Provide a quick summary. you'll start having Claude explain everything to you that it does, which will help you understand what Claude's building a lot better, which is critical if you are a new vibe coder. Which takes us to the next tip for me. I actually love how eager Claude is, and if it was up to me, I'd make Claude even more eager to do even more things and be more proactive. But if you find Claude is too eager and you want it to slow down and only do exactly what you want it to do, you can add this rule to your claude.md file, which is this rule right here. Do not act before instructions. What this does is slow down claude a little bit so it doesn't become as eager or as proactive. It'll make it so only does exactly what you ask it to do. I'd say this is one of the biggest differences between Codeex and Claude Code is Claude Code is very eager and anxious to make changes for you while Codeex does a little bit too little. And if you wish Claude Code was a little bit more like Codeex and slowed down and didn't do quite as much, you want to steal this rule here. But on the other hand, if you want Claude code to be more independent, more eager, more willing to take risks and take chances, you want to steal this rule, which is the default to action rule, which tells Claude that, hey, if you come up with new ideas, just implement them. You don't need to run them by me. Just implement them as they go and then I will approve afterwards. So, I'll put both of these down below. But if you want to adjust Claude's eagerness, you want to make it less eager, take this rule. If you want to make it more eager, take this rule. I actually like the more eager rule, so I'll be sticking with that one. And these rules that I'm giving you, I didn't pull these out of my rear end. These are straight from Anthropics blog, which again I link down below. The next tip straight from Anthropics prompting guide is to be super careful about how you use the word think. The word think is basically the only key word in Claude Code that actually changes how Claude code works. And if you use the word think, think harder or ultra think inside your prompts you give to Claude Code, it will make Claude code burn way more tokens. And so one issue a lot of people have is they say, "Hey Claude, think about this or think about why you want to do this." And they don't mean for Claude to triple the token usage. They just want Claude to consider something. And what happens is they burn through all their usage really quick because they're using the word think. So, you want to use alternatives to the word think if you don't want Claw to burn through more tokens. So, for instance, look at this prompt here. Give me a list of five new features we can add to our app. Consider which will have the biggest positive impact on user engagement. Typically, what a lot of people will do is think about which will have the biggest positive impact on user engagement. Or think about this. And the issue is is whenever you use the word think, that triggers Claude to burn way more tokens on this prompt. So, if you're using one of the cheaper tiers of Claude code, the $20 version or the $100 version, you want to be careful with your usage. And so, you want to be hyper vigilant about when you use the word think. If you want Claude to think without burning a ton of tokens, use alternatives like consider or evaluate rather than the word think. Which brings us to tip number eight, which is the fact that Claude Opus 45 is the greatest model of all time when it comes to vision. What does that mean? What does vision mean with Claude Opus? That means Claude can process images better and faster than any other model and they can do multiple images at once. So how does that impact claude code? This means you should be using as many images as possible with every single prompt you use. So there's two main reasons you'd want to use images in a prompt with Claude code. One is for inspiration. So say I want to take inspiration from another app I'm building. I want to take inspiration from my fantasy football app. All I would need to do is screenshot this and say put this into our prompt. So paste it right into the terminal. You can paste images right into the claude code terminal and say implement a UI that looks exactly like this. And what I could even do is include multiple screenshots inside here. So, if I want to take the UI from this other fantasy football site, copy that, paste that in. You can put really as many images as you want. You can see here now there's image one, image two. You can just add a ton of images in here as inspiration that Claude code will take from. And because Claude is so good at understanding images, it will take all of these into account in its prompts. The other way you should be using images is with bugs. So, for instance, I was in here before and I was searching for players from my fantasy football league and it wasn't showing all the players. And so, what I would do is I'd screenshot the screen, show how it wasn't showing all the players I was searching for and pasting that in. Anytime you get bugs or errors in your apps, you should always be using images because that will help Claude Code diagnose those bugs so much better. So, make sure you use as many images as you can in your prompts because Claude is so good with vision. Which brings us to tip number nine, which brings us right back to our claude.md file. This is another clawed rule straight from the blog post in Anthropic that you're going to copy and paste in. And that is the use parallel tool calls rule. And this is a big one. But let me explain how this rule works. Claude is the greatest model of all time when it comes to parallel tool calls. What does that mean? Claude Opus 45 can spin up multiple sub aents that all use multiple tool calls each. That means you can give Claude code a task and it can do research on the internet, create a document, look at different code files, write code and do all those at the exact same time. Then on top of that, it can look at images, understand images, look at video, all these different things all at once. No other AI model can do this quite like Claude. So what this rule is going to do is basically tell Claude to multitask as much as it can. Use as many tool calls as it can. Do it all simultaneously. And what that's going to do is save you tons of time. So instead of waiting for Claude to use tool calls one by one by one by one, it'll say, "Hey, when you need to feel free to spin up sub agents and have them spin up tool calls so we can get things done as fast as possible." This is all done via this rule straight from the anthropic blog. I didn't write this. I just copied and pasted it. I'm going to put this down below as well. Feel free to pause this video now. Copy and paste this into your own claw.md file so you get better results from claw code. And lastly, this is the 10th tip from the anthropic blog post that has prompting guides and all that. And that is a tip that will reduce hallucinations a ton in claw code. So yet another rule you're just going to copy and paste. These are my best types of tips because all you need to do is copy and paste things in and you're done. You get the benefits for life. You're going to paste in this investigate before answering rule. And what this does is have Claude investigate any code, reflect and review it before it makes any changes. So again, Claude is the most eager AI model ever and is very quick just to make changes, go in and make changes and screw things up. But if you put in this rule which is straight from anthropics blog post before it makes any changes to code it will review that code first so it understands it on a deep level. And this is one of the new benefits of having that amazing context window that Claude provides is it can review and remember code bases very easily. And so putting this rule in will make it so it doesn't hallucinate quite as much. It will do the proper research before making any changes. This is a recommendation Anthropic made directly right in their blog post and I've tested it out and I've gotten so fewer errors because of this rule. This is a big one. This is one you want to add. Now, this blog post, which I'll link down below, you can go in and read the entire thing yourself. There's others in here, but the 10 I gave you, I think, are the most important of the 10. If you learned anything at all, please leave a like down below. Make sure to subscribe. All I do is make incredible videos about AI. I also have a vibe coding academy if you want weekly calls with me, hackathons, and a whole community of other builders. The link for that is down below, too. We'll help you ship your first AI app in 21 days, which is incredible. I hope this was helpful. I hope this makes your clawed coding a lot more impactful. and I'll see you in the next
