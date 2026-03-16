---title: "OpenAI just released the #1 AI opportunity of 2025 (ChatGPT App SDK)"
video_id: "ZH-KZjDhpGc"
youtube_url: "https://www.youtube.com/watch?v=ZH-KZjDhpGc"
publish_date: "2025-10-14"
duration: "12:33"
duration_seconds: 753
view_count: 17421
author: "Alex Finn"
description: |
  The ChatGPT App SDK from OpenAI is the biggest opportunity in AI right now. Here's why and how you can build your first app with it.

  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinnX
  My $300k/yr AI app: https://www.creatorbuddy.io/

  ChatGPT App SDK:
  https://openai.com/index/introducing-apps-in-chatgpt/

  Visual Studio Code:
  https://code.visualstudio.com/

  Codex IDE extension:
  https://developers.openai.com/codex/ide/

  Prompt:
  Build a minimal TypeScript ChatGPT App: use @modelcontextprotocol/sdk with Express to expose a topMovers tool that hits Alpha Vantage’s TOP_GAINERS_LOSERS endpoint,  that, on load, calls window.openai.callTool('topMovers', { limit }), and renders responsive tables for the results inline in the widget. Have it run through a local server and ngrok. Please read through all the documentation here: https://developers.openai.com/apps-sdk/build/mcp-server

  Alpha Vantage API:
  https://www.alphavantage.co/

  Ngrok:
  https://ngrok.com/

  Timestamps:
  0:00 Intro
  0:25 How it works
  2:25 What we're building
  3:05 Building the ChatGPT App
  9:17 Configuring this in ChatGPT
  10:26 The final product

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
    - "OpenAI"
  people:
    []
  products:
    - "ChatGPT"
    - "Make"
    - "MCP"
  models:
    - "SAM"
concepts:
  []
summary:
  - "# OpenAI just released the #1 AI opportunity of 2025 (ChatGPT App SDK)

I'm going to show you how to build something really cool in this video"
keywords:
  - "ai-news"
  - "ai-strategy"
  - "ai-tools"
  - "chatgpt"
  - "coding"
  - "frameworks"
  - "make"
  - "mcp"
  - "openai"
  - "prompting"
  - "tutorials"
---

# OpenAI just released the #1 AI opportunity of 2025 (ChatGPT App SDK)

I'm going to show you how to build something really cool in this video. Open AAI just announced what I think is the single biggest opportunity in AI at the moment. Last week at their developer conference, which for the record, I was there and it was awesome. Sam Alman announced the ability to build native applications right inside of Chat GPT. On top of that, these applications will live in an app store that is fully monetizable, meaning you can sell these apps to whoever you want. This is absolutely massive. And here's a quick demo. You can just talk to apps inside of chat GPT and then the apps will actually be embedded. So if you say, "Hey Spotify, build me a playlist." It will inside chat GPT build you an entire playlist and send it to Spotify. This is massive and makes it really clear what Open AI strategy is with chat GPT. They're trying to make chat GPT an entire operating system that you never leave. When you go on the internet, they just want you going to chat GPT. They don't want you going anywhere else. But here's where the opportunity is in this that I think is absolutely mind-blowing. When new app stores launch on popular platforms, the first people to get apps into that app store make tremendous amounts of money. I don't know if you remember this, but when the app store on iPhone just launched, there were people just putting out like beer simulator apps where like you can just hold your phone up to your mouth and like beer went into your mouth on the phone. and they were making millions of dollars off those little tiny apps. This is like that except much bigger because there are way more people on ChatGpt than were on the iPhone when the app store launched on there. There are 800 million monthly active users on ChatGpt. And if you can capture even 1% of that audience with whatever apps you build for it, you are going to make tons of money. So, here's what we're going to do in this video. I'm about to show you how to build your own app inside ChatGBT. You can start building apps for now. It hasn't launched yet. It launches in a few months, but you can start building your apps now. If you follow along with this video, you will not only know how to build apps for the new Chad GBT app store. You will have your first app done. I'm going to show you end to end how to build your first app, even if you've never coded a day in your life before. So, stick with me. It's going to be tons of fun and you're going to be one of the first people in the entire world to have your own chat GPT app. Let's lock in. Leave a like if you want more content like this and let's get into it. Just as a quick preview of what we're building here, this is what a app inside ChatGBT looks like. You ask chat GBT a question that's relevant to whatever your app is. So, we're going to build a stock market tracking application that shows you the biggest movers in the stock market. You just ask, "Hey, what are the biggest movers in the stock market?" say Chad GBT will know to call your application, actually build an inline experience inside your app. So when people buy your app, anytime they reference the stock market, they're going to use your app. So this is going to actually be a really helpful and useful application that you're about to build out that a lot of people in chat GBT would be able to use. So I am inside the codeex plugin of Visual Studio Code. You can go ahead. I got the links down below for Visual Studio Code. It is completely free and then you can download the codeex plugin for it which will allow you to use codeex which is open AAI's coding tool. It's a part of your subscription with that. We are going to use codeex to build out and test our first chat GPT application. Feel free to pause, hit the link down below to get that installed or if you just want to watch me do it as well, you can do that. What I'm going to do is take a prompt and put it in here which I will also put the prompt down below. Now listen, this is a pretty detailed prompt. The reason why the prompt I'm about to show you is so detailed is because this is new technology. This is brand spanking new. Even Open AI's own models are not super familiar with it. So, I'm putting a detailed prompt that you can just copy and paste for me and use for yourself. So, what we're going to build here with this prompt is an app inside Chat GPT that shows users the top movers in the stock market that day. So if anyone's using Chad GBT and they ask, hey, what are the top gainers in the stock market today or top losers, it will call our application, actually show them in the app all the stocks that move that day with live data. So this is actually a really cool and really helpful app that users will probably buy right off the rip when this launches. And even before it launches, you can start using this app on your own and it's going to be really helpful. So here's how we're going to build that market watching application. Build a minimal TypeScript chat GPT app. use the MCP SDK with Express to expose a top movers tool that hits Alpha Vantage's endpoint. So, we're using Alpha Vantage API, which is a really popular stock market API to get the data for our app. That onload calls an open AI endpoint. What that's going to do is actually put the data live in the application and renders responsive tables for the results in line in the widget. Have it run through a local server and enro. And don't worry, I know this sounds really, really technical. I'm going to walk you through everything. you'll have this done, I promise, even if you've never coded before. And please read through all the documentation here. So, I give them a reference to the OpenAI docs so that it knows precisely how to build it and how it works. This prompt, I know it sounds technical, but I promise bear with me. Copy and paste it. This is going to get us a working app for the Chat GPT app store. For this, I'm going to use codeex medium. So, this isn't too complicated, but I wanted to use medium just because a lot of this is new functionality. And I'm going to hit enter on this. And Codeex is going to get to work building out this application for us. As this is going, if you've learned anything so far, make sure to leave a like down below. Make sure to subscribe. All I do is create amazing content around building with AI. Also, make sure to sign up for my free newsletter down below. It's called Ship It. It's the number one AI newsletter out there. So, hit that link as well. So, it's going to start planning out the TypeScript application for us. It's going to start inspecting our repository. And now, as you can see, it's actually reading the documentation so it knows how the new chat GBT app store works and it's going to get to work on building our app. And as a quick preview of the tasks, it's going to do it's going to look through any code we already have, which is none. You're just going to open up a new project for this. It's going to implement the MCP server, which is going to be feeding data to chat GPT. It's going to create the widget, and then it's going to document the setup. As this is building, I was at the conference last week, and I'll tell you, this is the part that blew me away the most. more than the agents, more than everything else he did. This blows me away. I'm always looking for the opportunity early to consumer technology and this is it. Everyone is going to be using applications in the chat GPT store. So, you're going to want to make sure you have the first applications in there. If you're on there day one, there's going to be people that go into the app store and just download all the apps. And yours is going to be one of the apps they download. I really believe there's going to be one person businesses that make millions of dollars day one building out applications in this app store. So, it's so good that you're watching this video and building this out with me because you're going to have an app ready to go, ready to ship the moment the app store launches. Let's check over here on what Codeex is doing. Looks like it is starting to build out the code for our MCP server. That is nice. And then it's going to get into the front end and documenting everything. We're going to be testing a really cool app in a second here. All right, looks like it finished coding. Now, I'm going to show you how to set this up to get it working. It takes a few steps, so bear with me here. Very, very simple. What we're about to do, the first thing we're going to do is get the Alpha Vantage API key, which is free and easy to get. So, what you want to do first is set up the environment variable. So, we'll come into our files here. There's enenv.ample where you'll see the spot for Alpha Vantage key. What we're going to do is we're just going to do a new file. Env.local. Hit enter on that. Copy everything from the example file, paste it into local, and what we're going to do is just get this Alpha Vantage key. If you go to alpha vantage.co and then click on get free API key, all you do is put in your email address and they'll give you a free API key in like seconds. It's very, very easy to get. Copy and paste that in. Next, what we're going to want to do is just follow the instructions here. So, we're going to want to go to our terminal, which if you're on Mac is control day. I'm sure it's whatever the bottom left and top left keys are on your keyboard if you're on PC. and we're going to do npm rundev as it asks for. Okay, looks like it's running. And then what we want to do now is we want to use enro to pipe our server to chat GPT. Now, I know that sounds really confusing, but it's simple. Bear with me here. Chat GPT can't read from your local server. So, what we're going to do is use a tool called Enrock that will basically link our local server to the internet. So, you're going to want to do this. I'll put the link for this down below. Just install Enro inside your terminal. That will get the technology on your computer. Once you do that, I promise you it's safe. Every all the developers use it. You're good to use it. Once you do that, all you're going to need to do is type in nro http 3000. This should be the server, your local host server that's running, which should be 3000. Once you do that, you hit enter. Now, Enro is running on your computer, which is piping your local host, basically your MP MCP server to the internet. So, you're good to go. Now, we're just going to want to configure this inside chat GPT. So, if you go into chat GPT, hit your name, and then go into settings. From there, you can hit apps and connectors. And once you're in here, if you go down to advanced settings, you want to make sure you turn on developer mode. So, make sure that's turned on there. Once developer mode's turned on, you'll get this nice little create button in the top right. You hit create. We'll come in here. We'll give our app a name. So, I'm going to give this app the name Market Watch. So, then we go down. We're going to need to put in our MCP server URL. So, this is very simple. All we're going to do is you go back in inside Enro. You copy this link right here. Right? So, it has the address right there. We go back in here, we paste it in, and then just make sure you do slashMCP at the end. That is going to set up your server for chat GPT authentication. We do no authentication and we say we trust this application. All right, we're good to go. We're going to hit create here. Now, we're going to test this out. We're going to see if this works. So, the first thing you want to do is tag your application. So, we're going to do at marketwatch and then we're going to say what are the current movers. All right, let's see if this works. Let's test out our app here. This is very exciting moment in time. So, it's going to look for available tool. So, it's going to look for our app. It found our app. It's calling the new application we just built. We're going to confirm the call it's making to the tool. So, I hit confirm there. And then boom. Look at that. There we are. You can see here, Market Movers top 10 gainers. So, it has the top 10 stocks that gain today and then the top 10 losers. And it's all in this really nice inline widget that's inside of Chat GPT. So, it's an application built right into the chat. And so, now anytime a user who gets your application asks about the stock market, it is going to load up your application that you built out. Now, imagine if you're the first one to the Chat GPT app store with a stock market app or with a weather app or with whatever app you want to build out. That is going to be a huge, massive advantage. And now you have your app good to go. The app store does not launch for another few months. So, you can keep working on this now. You can add to it. You can add more functionality and then when it launches in the next few months, you can put it up there. Be one of the first up there and start making money off this. This is such a massive opportunity. You need to jump on the latest tech the moment it comes out. And let me tell you this, this app store. Come to Chad GPT. This is the latest and biggest opportunity in AI at the moment. This app store is going to be massive. It's going to be on the same level as the iPhone app store. I mean, there's more users of the Chat GPT app store than there is the iPhone app store when it came out. So, this is massive. Keep working on this stock market template if you want. If you don't want to go back, take the prompt I gave you from down below, make it your own, and work on a different app. If you want to work on an app that's in a different realm, you can do that as well. Just make sure at the end of the day you're building. Even if you have no idea what to build here, just build something. Eventually, the idea will come to you and you'll have something awesome. If you learned anything at all, make sure to leave a like. That lets me know you want more content like this. Sign up for my free AI newsletter. Ship it. Link is down below as well. Subscribe to get more awesome AI content like this. and I'll see you in the next
