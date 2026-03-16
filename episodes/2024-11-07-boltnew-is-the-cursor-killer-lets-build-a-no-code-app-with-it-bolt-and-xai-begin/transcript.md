---title: "Bolt.new is the Cursor Killer. Let's build a no-code app with it (Bolt and xAI Beginner's Guide)"
video_id: "Z9WxOhrl-3U"
youtube_url: "https://www.youtube.com/watch?v=Z9WxOhrl-3U"
publish_date: "2024-11-07"
duration: "9:10"
duration_seconds: 550
view_count: 6920
author: "Alex Finn"
description: |
  In this video we use the Cursor killer (Bolt.New) to build a stock analysis app. We use the xAI API to feed in real time data as well.

  Make sure to follow my X and subscribe to my newsletter!
  X: https://x.com/AlexFinnX
  Newsletter: https://www.1percentbetter.io/subscribe


  Bolt:
  https://bolt.new/

  xAI:
  https://console.x.ai/

  Computer Use github:
  https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo

  0:00 What we are going to build
  1:11 Bolt intro
  1:48 Start building
  3:12 Charting complete
  4:03 Hooking up price data
  5:26 Real time pricing complete
  6:05 xAI API key
  7:43 Real time data implemented



  #ai #aiagent #xai  #technology #artificialintelligence #bolt

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Tools"
difficulty: "Beginner"
audience:
  - "Engineers"
  - "Executives"
  - "Product Managers"
entities:
  companies:
    - "Microsoft"
    - "Nvidia"
    - "Cursor"
    - "X"
    - "Bolt"
  people:
    - "Elon Musk"
  products:
    - "Cursor"
    - "Make"
  models:
    []
concepts:
  []
summary:
  - "new that's the URL put it into your browser the reason I'm excited to use bolt"
keywords:
  - "ai-news"
  - "ai-tools"
  - "bolt"
  - "career"
  - "coding"
  - "cursor"
  - "deep-dives"
  - "make"
  - "microsoft"
  - "nvidia"
  - "product-management"
  - "prompting"
  - "tutorials"
  - "x"
---

# Bolt.new is the Cursor Killer. Let's build a no-code app with it (Bolt and xAI Beginner's Guide)

we're about to build something so freaking cool I'm going to show you how to build a stock analysis app powered by real time data from the xai API no programming experience necessary at all if you've never been a line of code in your entire life you're going to be able to build this really cool app the best part is you'll be able to use this yourself to get your own stock analysis or you can even put this on the internet and sell it to other people and make money you don't need a single second of programming experience to build this this is built for beginners for those that don't know bolt. new is a really powerful web app that lets you build software with AI no programming experience all you just write it a prompt and it builds an app an X aai is one of the most powerful AIS out there today it's Elon Musk Ai and it's built on Real Time data coming from social media so that's really really powerful for those who don't know bolt. new is a sick web app that allows you to build any app you want with is a couple AI prompts so buckle in follow along here pause when you need to by the end of this video you'll have your own stock analysis app that you can either a use for yourself or B put on the internet and sell to people and make money off of and start your own business let's get into it so we're starting here on bolt. new that's the URL put it into your browser the reason I'm excited to use bolt. news they just released a massive update that makes it much faster and easier to use anyone can use it you don't need to be a developer all we're going to do is we're going to put in a prompt here of what we want to build bolt. new all by itself is going to write the code for us and we won't have to do any work whatsoever I'm also super excited cuz xai what I'm about to show you as well just dropped it is the sickest AI out there we'll be able to pull in realtime data from the internet which is going to be awesome to power this stock analysis app by the way this is free you can create a free account start building apps right away so let's do this let's tell bolt. new exactly what we want to build So I entered create a stock analysis tool it should have a search bar where you can enter a stock symbol display a price chart using recharts and show AI powered in sites using the xai API make it beautiful feel free to pause here copy paste that put that into your own app I'll make sure to put all the prompts down below so you can just copy it from the description but this is how simple bolt. new is I can just hit enter here and it's going to start building our app for us I'll help you create a beautiful and professional stock analysis tool since we'll need additional packages for charts and API handling let's add them first so it's just going to start as you can see here on the right building all the code for us I'm not doing anything look mon No Hands it starts installing all the Technologies writing the code and all I and all I need to do is sit here and watch which is pretty sick again you don't need any programming experience for this at all what's really amazing about bold. new as this app builds out is you can come up with any app ideas on the Fly and just build it out immediately that's never been possible before we've never had the opportunity for people with zero technical skills just to start building apps on their own so that's what makes us really really cool side note as this is building if you've learned anything so far make sure to hit the Subscribe button turn on notification so you get breaking AI news the moment it happens leave a like and let me know what you want me to build next every video I make is based on user feedback all I do is build really cool AI videos okay so we one shot prompted this let's see what we got here I've created beautiful and professional stock analysis tool with the following features a modern clean UI this UI is actually sick uh I really like the stock chart so let's test it out let's put in a stock let's put in uh Nvidia everyone's favorite stock let's search let's see how this does okay so it's got the price for NVIDIA so this looks really good I like the way the chart looks okay we can get signals we can get sentiment let's get it gives us risk alert I like that this thing looks beautiful so it looks like we got the UI done here now we just need to put in the data sources right so let's first get in the realtime stock market data so we can get the prices and the chart to fill out here so this is just like having your own developer right you're not writing in code yourself you just tell the developer hey I want to build this out I want to build this out I want to build this out then it goes and does that for you so let's connect this to Market data you can use the alpha Vantage API for those who don't know Alpha Vantage API it's just realtime stock market data that comes in so feel free to copy paste that we'll hit enter okay it says I will help you integrate the alpha Vantage API for real-time Market data first let's create the service layer okay so it's going to write all the code for getting the data it's probably in a second going to ask me for an API key for Alpha Vantage I'll show you step by step how to do it will be super simple that's all getting built out right here it's it's pretty amazing uh how quick this is bolt. new I'm really impressed with bolt. new all right looks like it created the service layer all I need to do is put in an API key in stock api. TS okay you can see right here API key equals demo so let's get the API key if you go to alphav vantage.adp key so I got this one here I'm going to copy it we can go back into the code here we can replace demo with the API key hit save that is saved and last thing just make sure you put in your API key in quotes here too so paste in your API key here into stock api. TS put it inside the quotes hit save then we come back into the preview up top here let's test this out let's see how this goes Nvidia search come on baby give us some good information oh boom look at that that is beautiful that is the real time data that is the that is the share price I myself got a few few shares of Nvidia so I'm very happy about this stock price very happy price go up okay so we got the real time data coming in for the stock prices now let's use now let's do the cool part let's get the realtime information coming in from xai so I'm going to come back over here into our AI with this for the record we got all this with just two prompts so far two prompts let's do a third prompt and get this realtime data coming in to use the xai API your go going to need an API key so what you can do is go to console. x. a sign up for that come in here you can create an API key now you have your API key there's one small thing we're going to want to do here to make sure bolt. new knows about this because this literally just came out today we're going to want to go to the docs and follow along feel free to pause here as I'm doing this once you're in the docs click Integrations and then come down here it says JavaScript just click copy just copy that this is how xai works and we're just going to tell bolt. new this is how it works I come in to bolt. new please use the open AI I want to use the X AI API to bring in information about the company we search for please use the open AI SDK for the X a API here is what it looks like then I paste that in I hit enter just so it knows what the xai cuz it's brand new we're using the most Cutting Edge technology here I'll help integrate the xai API to provide int insights about companies I'll update the necessary files to include this functionality so boom it's going back we're on our third prompt here we have a full application with three prompts it's building out the code and in one second we're going to have real time company data coming into this app all right so now we just need to get our API key from xai so go back in so go back in go to your console create your API key when you create it it's going to give it to you just copy and paste that and then you go back in here it says AI service all right we look for AI service and then you put in your API key right there you just paste it in and for the record if at any point the app is not showing up in the preview section all you need to do is type in npm runev to the terminal down here you just type that in and you're good to go all right so we're back in here let's test this out this time let's go on Microsoft let's see what they give us for Microsoft oh wow look at this this is sick okay so we get the this is all coming in from the xai API we get the price Movement we get the volatility analysis High volatility Ed exercise caution we get the business performance Microsoft business performance Microsoft report a strong fiscal Q3 with a 10% year-over-year Revenue increase future Alec anist project continued growth for Microsoft Market position Microsoft holds a dominant position in cloud computing this is sick this is all coming in from xai this is all realtime information from uh from social media feeding into here this is sick we built this in three prompts and there's so much we can do from here right if we want to now put this on the web and allow people to subscribe to it for $5 a month we can do that because this is a pretty sick app where you can get realtime analysis if we want to add more functionality we can do that I think a really easy one can be let's put out a watch list right the ability to save a watch list all we'd have to do is go on bolt here on the left type in build me a watch list and it gets built out this is really sick if you have not played around with bolt. new yet if you've not played around with the xai API I'm going to put both Down Below in the description this is sick all I do is make videos showing you the coolest new AI technology and how to use it to build stuff make sure to hit subscribe turn on the Bell leave a like if you learned anything let me know what I should record for my next video see you guys then
