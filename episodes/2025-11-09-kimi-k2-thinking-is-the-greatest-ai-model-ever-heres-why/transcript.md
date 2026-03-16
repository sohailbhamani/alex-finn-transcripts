---title: "Kimi K2 Thinking is the greatest AI model ever. Here’s why…"
video_id: "jQVb7t62VHM"
youtube_url: "https://www.youtube.com/watch?v=jQVb7t62VHM"
publish_date: "2025-11-09"
duration: "14:20"
duration_seconds: 860
view_count: 24475
author: "Alex Finn"
description: |
  Kimi K2 Thinking is the best AI model I've ever used. In this video I go over why and show you how to build your own deep research app with it.

  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinnX
  My $300k/yr AI app: https://www.creatorbuddy.io/

  Kimi:
  https://kimi.com

  Prompt to build your own Kimi Research app (I used Claude Code to build it):
  Build a Kimi K2 Thinking Demo App Create a web app that demonstrates the Kimi K2 Thinking model's extended reasoning and multi-tool capabilities. The app should:
  Tech Stack: Next.js, TypeScript, Tailwind CSS v3, React
  Features:
  Accept research queries (e.g., "Compare Notion, Obsidian, and Roam Research")
  Display real-time thinking/reasoning as it happens
  Show all tool calls as they execute with arguments and results
  Display metrics (thinking tokens, tool calls, elapsed time, input/output tokens)
  Show final research report in markdown
  Tools: The model should have access to:
  web_search: Search the web for information (use Tavily API)
  analyze_data: Execute Python code for data analysis and visualization
  create_pdf_report: Generate professional PDF research reports
  UI Layout:
  Input area for research queries with 3 example prompts
  Metrics panel showing real-time stats
  Three-column layout showing: Thinking (left) | Tool Calls (middle) | Results (right)
  Each panel scrolls independently with 600px fixed height
  API: Use the Moonshot API (Kimi K2 Thinking model) with streaming responses
  Example Queries:
  "Research Notion, Obsidian, and Roam Research. Find pricing, create a comparison chart, and generate a PDF report."
  "Analyze the top 3 AI coding assistants. Research pricing and features, create visualizations, and export a PDF."
  "Research cloud storage providers. Find pricing tiers, calculate cost per GB, create a chart, and generate a PDF decision matrix."
  Environment Variables:
  MOONSHOT_API_KEY (from Moonshot AI)
  TAVILY_API_KEY (from Tavily)


  Timestamps:
  0:00 Intro
  0:39 Why Kimi is incredible
  3:54 Benchmarks
  4:58 When to use it
  5:20 Demonstration
  10:20 Instant code review
  11:32 How to build your own Kimi researcher

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
    - "Anthropic"
    - "Notion"
    - "Tailwind"
  people:
    []
  products:
    - "Claude"
    - "Claude Code"
    - "Make"
    - "Sonnet"
  models:
    []
concepts:
  []
summary:
  - "Here’s why…

Kimmy K2 thinking is the best AI model I've ever used"
keywords:
  - "ai-agents"
  - "ai-news"
  - "ai-tools"
  - "anthropic"
  - "claude"
  - "claude-code"
  - "coding"
  - "frameworks"
  - "make"
  - "notion"
  - "sonnet"
  - "tailwind"
  - "tutorials"
---

# Kimi K2 Thinking is the greatest AI model ever. Here’s why…

Kimmy K2 thinking is the best AI model I've ever used. What I'm about to show you and the capabilities of this model are going to blow your mind. This is going to be the AI model that starts replacing human beings. We finally have an AI model that can work for hours on end with no hallucinations and hundreds of tool calls. If you stick around with me until the end of the video, you will understand exactly what Kimmy K2 is, how it works, what makes it special, and I'll even show you how you can start building apps with it today. I'll walk through step by step how to build an app for it yourself, even if you've never written a line of code in your entire life. Let's get into it. So, Kimmy K2 Thinking just released. This is from the Chinese company Moonshot, and it is actually incredible. What makes Kimmy K2 thinking so special? Well, a few things. One, it is the most agentic independent model ever made. Meaning, it can run for hours by itself, making hundreds of tool calls doing stepbystep complex workloads, all without hallucinations or you having to intervene with what it's doing. How does it pull it off? How does that achieve it? Well, a few different ways. Number one, it uses something called interled thinking. And I'm going to show you an example of this in a second when we build out our own app with Kimmy K2 thinking. Basically, what interleved thinking is is the model's ability to plan, act, verify, reflect, and refine. So, as it goes, it's actually reflecting on what it's thinking about. Right? So, it'll do a bunch of thinking, use tools, take action, and then reflect on what it did and determine if it accomplished its goal or not. Then, based on that, we'll do different thinking and more improved thinking. So as it goes, it actually gets smarter rather than what most AI models do, which is think think think and then along the way it gets lost and doesn't know what it's doing. Simply put, it is able to think and reflect every single step of the way. So it never gets lost. And that is really important. That is a massive improvement in AI technology. Why is that? Because now the AI model can be way more independent. You can give it tasks and because it is able to reflect and determine what to do, it can work independently for hours on end without human intervention or hallucinations or errors or anything like that. This is the first step toward an AI model being able to actually replace human being. Many other improvements here. It is built for tool calls. So it can do hundreds of tool calls on its own without human intervention. What are tool calls for those don't know at home? This is the AI's ability to use different tools at its disposal to accomplish its goals like web search or writing code or creating documents or creating charts or running code or anything you can think of. It's the ability for the AI to use different tools. So now you not only have the ability for the AI to think non-stop on its own, but you also have the ability for the AI to actually take action on its own. This is how we close the gap between what AI can do and what human beings can do. It has a massive context window so it can remember a ton. It can work for hours and remember everything it did over those hours. Here might be the best part of it all. It's extremely cost effective. So it's actually half the price of chat GBT5 and on top it's about a tenth of the price of Sonnet 45. So this varies on what it's doing but it is basically a fraction of the cost of all the mainstream foundational models people are using right now. And then maybe even more revolutionary than that, it is completely open weights. So you can download it right now, run it locally. It doesn't need access to internet and have it run on your machine. Now, you do need a pretty good machine to run it locally. Right now, if you want to run it locally, the mainstream devices you need are two Mac Studio M3 Ultras, but that doesn't matter. They're open weights. Kimmy said, "Here's the model. Do it with it whatever you want." Which is really, really amazing. So, it's a fraction of the other AI models. It is completely open weight and it is just as good if not better on almost all tasks. So when it comes to humanity's last exam which is a really big test for these AI models to see if they are smarter than human beings it is the best out of all of them. When it comes to agentic tasks it is the best out of all of them compared to chat GPT uh and anthropic. The only places where it might be just as good if not lacking a little is on the coding side. Sonnet 45 still appears to be king of coding. I will still probably be using clawed code even with this out unless someone wants to send me two Mac Studio M3s then I'll be running it locally and building the code with Kimmy but it is just as good if not better in almost every single area and it is a fraction of the price. Man, that is incredible. So I'm going to go into a demo in a second. I'm actually going to build out an app using Kimmy K2 thinking. You can follow along. You'll have your own AI agent built out that you can use if you follow my steps. But when would you want to use this model? Where does it shine? When you're building really anything complex, anything agentic. So, anything that's a multi-step AI workflow, you're going to want to use Kimmy K2 because it can think independently. It can work for a long time and it can use multiple tools. Basically, anything where you would want your own employee or a human being doing something, that's what Kimmy K2 thinking is going to be really, really good at. So, if you want to test it out yourself, you can test it out right now for free. You go to kimmy.com and then you click the light bulb to put on thinking mode and you have complete access to the model. So, you can just start using it right now. But where I'm going to use it is through the API to actually build out an entire Agentic app. So, I built out a custom demo app to show you just how powerful this model is. So, you can see all the tool calls it uses. You can see the inner leaf thinking, the really advanced reflection and thinking it does and show you the results you can get out of this. Right after I'm done showing you this demo, stick around. I'll actually give you the prompt you can put into Claude Code to build out this demo so that you can have your own deep research Kimmy K2 thinking app that you can use your own AI agent. I built this all with one single prompt. This was one shot with Claude Code and you're going to see just how powerful this model is. So, with this demo tool I built, which you can build out after this, you're able to enter in any sort of research prompt you want, and it will use Kimmy K2 thinking to do this really deep, awesome research, which you really can't get with any other tool. I have some example prompts here. We're going to use one of these example prompts. So, what it's going to do is research notion, Obsidian, and other note-taking tools. find their pricing, compare their pricing functionality, and generate a professional research report comparing all of the notetaking tools. So, I'm going to put in that demo prompt that's part of this tool, which you'll be able to take as well. At the end, I'm going to start the research, and what you're going to see here in real time, what's going to happen is you'll be able to see the interled thinking, which basically you'll see all the thinking, all the reflection it's doing to determine what to do next. You're going to see all the tool calls it does independently. So you can see how it thinks, what tools it uses, and how it's able to work independently. And you can see it happening in real time here. Up here, you'll be able to see the elapse time, how long it works, the amount of tool calls, the amount of tokens it's using. Uh just to see how incredible this is. So you can see here the user wants me to research three knowledge management notetaking tools. It's building out a plan for how to do that research. It has started the research on the web. So, it's doing a bunch of web search tool calls. So, it's searching the web for notion pricing. It's searching the web for Obsidian pricing. And then you can see the results it's getting here. And this is a tool you'll have you can use if you stick with me here. So, you can run your own long research reports and get some really amazing information like you see here. It's researching a tool called Rome research. So, you see so far we're only 1 minute in. It already has nine tool calls. It's already done a ton of thinking and reflection. Let's scroll down here and see all this. Oh, so we're on the 10th tool call now where it is searching for what you get in the Obsidian $10 tier, right? So, it's able to look at the results is getting from its search, see if those results accomplish the goal it's looking to accomplish and then based on that answer is able to come up with its next queries. So, it's taking action, it's reflecting, and then it's taking action based on those reflections so that it never hallucinates. it's always able to move closer and closer to the goal you're trying to accomplish. This interle thinking is really really revolutionary because basically the way these models were working before was it would take a step, it would take a step, it would take a step, it would just keep taking steps hoping that it would eventually hit your goal. And a lot of times AI models, if it's a really long task, they'd get lost, confused, and not be able to accomplish the goal and start hallucinating. With interled thinking, what it's able to do now is actually reflect every step of the way. Take a second, pause, go, okay, am I getting closer to the goal? Did the information I just get help answer the question the user has? And if not, how do I get closer to that goal? Which is just going to make your AI agent so much smart? I mean, that's how human beings think, right? That's how human beings operate. You don't just go down a path and not think about what you're doing. You reflect and go, okay, am I taking the right steps down this path? So the AI is becoming a lot more humanlike. And as this works, you can see here it's now using the analyze data tool to actually analyze all the data and information it got using Python, which is really, really cool. I know earlier in the video I said, oh, this is like the first step toward AI replacing human beings. And I know that can scare a lot of people. I know people instantly think, oh my god, people are going to lose their jobs. This is horrible. The way I like to think about it is this. It's not about taking away from human beings. It's about adding to what human beings are capable of. Right? I'm a oneperson business. I'm going to be honest with you. I don't make enough money to hire a bunch of people. I do all my own editing. I do all my own scripting. I write all my own content. I build my app myself. I write all my own code. This is about giving people like me the power of an entire corporation. Right? If I have a bunch of Kimmy K2 models working for me, it's like I have multiple employees. And now people like you and me that might be a little bit more independent are able to have the power that huge corporations have because I can have these AIs working for me. If it wasn't for AI, I wouldn't be able to be this productive. But because of AI, I now have the productivity of multiple human beings working for me all for what this probably costs like two cents to make. That's the way I would think about this. This isn't replacing human beings. This is just giving human beings way more power. And now you can see as I was talking there and rambling on to you, it finished the report. So it used the analyze data tool to analyze all the data compiled from all its web searches and queries. And then it used the create PDF report to build the actual report itself, which you can see a markdown preview of right here. So it shows you an entire report on all the different writing tools and what it came up with. Top recommendations for individuals, start with Obsidian for free. Then for researchers, try Rome research. Right? So it came up with an entire research report based on all the tool calls. It worked for 4 and a half minutes, did 12 tool calls and thought with 173 tokens. I now have my own research assistant. Typically I need to pay thousands of dollars to hire someone before. Now I can use Kimmy K2 to do this really deep intense research. Now the part I promised to you how to build this yourself. How to get this? Open up Visual Studio Code. Install the Clawed Code extension if you haven't already. We're going to be using Claude Code for this. Open up the Claude Code extension. And I'm going to put this prompt below so you can just steal it. Build a Kimmy K2 thinking demo app. Create a web app that demonstrates the Kimmy K2 thinking model, extended reasoning, and multi-tool capabilities. The app should we're going to build it in Nex.js, TypeScript, Tailwind, CSS, React. It's going to be able to accept research queries, display real-time thinking as it happens, show all the tool calls, display the metrics, and show the final research report. It shows all the tools it's going to be able to use. It has the UI layout. It uses the Moonshot API, which is the company that made Kimmy K2 thinking, and it shows a few example queries for this. We'll use the Moonshot API key to run Kimmy K2, as well as Tavi, which is a web search tool that Kimmy's going to be able to use to do the searching. You hit enter on that and Claude Code is going to start getting to work building that app out. It's going to create all the to-dos for you and it will independently, you can click yes and don't ask again, start building that app out for you. That prompt is down below. Really awesome afternoon project you can build out on your own. You can do it in between commercials for the football game if you're watching that right now. Hit enter on that. Build that out. Really awesome project you can build. And at the end of it, you'll have your own AI research assistant. There's no technical knowledge needed here. Just send that prompt and you have your own advanced maybe most advanced in the world AI research assistant leveraging the most powerful AI technology there is. Once that is all done, you just do npm rundev in your terminal. Well, you hit control till day. Then you hit enter on that. It is going to run it and you'll get your research screen here with your example prompts. Or you can just prompt whatever you want and have it research whatever you want. But Kimmy is absolutely incredible. Moon Moonshot, if you're watching this and want to send me a couple Mac Studio M3 Ultras, feel free to send it my way. I'll make a hundred videos about Kimmy K2 on it. This is really amazing. It is now my dream to run this locally so I can have my own local 247 AI employee just doing research and working for me. You got to be using this. You got to be using the latest AI tools the moment they become available. This is how you stay on the cutting edge and stay ahead of your competition. And let me tell you this, Kimmy K2 thinking is on the cutting edge right now. I can't wait to see how Open AI and Anthropic respond to this one. This is amazing. I hope you learned something in this video. If you learned anything at all, leave a like, subscribe, turn on notifications. All I do is make amazing AI content videos like this. Also live stream three times a week, Monday, Wednesday, Friday, 11:00 a.m. Pacific Standard Time. Also, check out my free AI newsletter in the description below. and I'll see you in the next video.
