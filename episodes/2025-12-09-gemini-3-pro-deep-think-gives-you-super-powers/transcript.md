---title: "Gemini 3 Pro Deep Think Gives You Super Powers"
video_id: "lWAH-gCQRbA"
youtube_url: "https://www.youtube.com/watch?v=lWAH-gCQRbA"
publish_date: "2025-12-09"
duration: "12:13"
duration_seconds: 733
view_count: 9666
author: "Alex Finn"
description: |
  Here is why Gemini 3 Pro Deep Think is so powerful and how you should be using it!

  Join the Vibe Coding Academy: https://www.skool.com/vibe-coding-academy
  Sign up for my free newsletter: https://www.alexfinn.ai/subscribe
  Follow my X: https://x.com/AlexFinnX
  My $300k/yr AI app: https://www.creatorbuddy.io/

  App prompt:
  You are a brutally honest product strategist for solo “vibe coders” who don’t know what to build.
  Your job is to generate specific, realistic app ideas a solo builder can ship, not generic “start a SaaS” nonsense.

  Here is the person:

  Skills: Advanced vibe coder
  Tech comfort: Really good with web apps
  Time available: An hour a day
  Existing audience (if any): 50,000 on Youtube
  Interests: AI, vibe coding, entrepreneurship
  Money goal (for this project): $10,000 a month
  Risk tolerance: High
  Based on this, produce 3–5 concrete app ideas using this structure:
  For each idea:

  Idea Name & One-Liner

  A clear name and 1 sentence that explains what it does and for who, in plain language.
  Why This Fits You

  3–5 bullets mapping directly to the info above (skills, time, audience, interests, money goal).
  If something is a stretch for their current skills, call it out.

  Scope & Time-to-Ship

  Label as one of: “Weekend prototype”, “21-day build”, or “Longer (not recommended yet)”.
  Explain what v1 actually includes (no bloat, no extra features).

  Tech Stack & AI Workflow

  Recommend a simple stack (e.g., “Next.js + Supabase”, “iOS + SwiftUI”) that matches their skills and time.

  Explain how to lean on AI tools (Claude Code / Cursor / ChatGPT) for the hardest parts.

  Go-To-Market Angle

  How they would get the first 20–50 users given their audience (or lack of one).

  2–3 concrete channels or tactics, tied to their context.

  Risks & Dealbreakers

  The 2–3 biggest risks for this idea.

  A simple test they can run in less than 1 week to see if it’s worth pursuing.
  Rules:

  Do NOT suggest anything that clearly doesn’t fit their time or skills.
  Avoid vague ideas (“build a platform for X”). Make each idea as specific and narrow as possible.
  If you think their inputs are unrealistic (e.g., no skills, no time, $10k/mo goal), call that out directly and adjust ideas accordingly.

  SPACE SIM PROMPTS:
  You are a senior physics simulation engineer and JavaScript developer.

  Your job is to design AND implement, in one shot, a browser-based 3D orbital simulator that is *actually* physically reasonable and visually impressive, not just boilerplate Three.js.

  **High-level goal**

  Build a single-page app that runs in the browser and shows:

  * A star at the center
  * One planet orbiting the star
  * A spacecraft whose trajectory is influenced by gravity (can do fly-bys / gravity assists)
  * Camera I can orbit around the scene
  * A visible trajectory trail for the spacecraft

  Use JavaScript + Three.js (from a CDN) in a single HTML file I can drop into an empty folder and open in the browser.

  ---

  ### 1. Think first: design the physics & numerics (no code yet)

  Before writing any code, think step by step and **write out your reasoning**:

  1. Define the physics model:

  * What forces are present?
  * What simplifications are you making (e.g., 2D plane embedded in 3D, point masses, ignore relativistic effects, etc.)?
  * What units and scales will you use so that numbers are numerically stable and visually reasonable?

  4. State & architecture:

  * Define the data structures for bodies: position, velocity, mass, etc.
  * Define the simulation loop: compute forces → integrate → update meshes.
  * Explain how rendering (Three.js) is cleanly separated from physics.

  **Do NOT write any code until you finish this design section.**

  ---

  ### 2. Then write the full working code (one HTML file)

  After you finish the reasoning above, output a single complete HTML file that:

  * Includes Three.js from a CDN.
  * Sets up:

  * A scene, camera (orbit controls), and renderer.
  * A star (bright sphere at the origin).
  * A planet orbiting the star.
  * A spacecraft whose motion is affected by gravity from the star and planet.
  * Implements the physics model and integration method you designed.
  * Runs a render loop that:

  * Updates physics at a fixed time step.
  * Updates object positions.
  * Renders the scene.


  Visual requirements:

  * Add a visible trail for the spacecraft (e.g., using a dynamic line or small particles) to show its path.
  * Make the star, planet, and spacecraft visually distinct (different sizes/materials).
  * Reasonable default camera position that frames the system well

  ---


  0:00 Intro
  0:25 How it works
  3:23 Demonstration
  6:37 Space simulator demo
  7:15 Prompt to use today
  11:10 When to use each AI model

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Strategy"
difficulty: "Advanced"
audience:
  - "Engineers"
  - "Executives"
  - "Product Managers"
entities:
  companies:
    - "Google"
    - "GitHub"
    - "Cursor"
  people:
    []
  products:
    - "Claude"
    - "Claude Code"
    - "Gemini"
    - "Cursor"
    - "Make"
    - "Opus"
  models:
    - "Gemini"
    - "Gemini 3"
    - "Gemini Pro"
concepts:
  []
summary:
  - "# Gemini 3 Pro Deep Think Gives You Super Powers

Gemini 3 Pro Deepthink is the latest AI model from Google"
keywords:
  - "ai-tools"
  - "claude"
  - "claude-code"
  - "coding"
  - "cursor"
  - "frameworks"
  - "gemini"
  - "github"
  - "google"
  - "make"
  - "opus"
  - "product-management"
  - "prompting"
  - "tutorials"
---

# Gemini 3 Pro Deep Think Gives You Super Powers

Gemini 3 Pro Deepthink is the latest AI model from Google. It takes the already revolutionary Gemini 3 and makes it even better. This model will change how you use AI. In this video, I'll show you what makes this one of the most revolutionary AI models ever. Show you a mindblowing demo, then give you a prompt that you can start using today that will make you way more productive with Gemini 3 Pro Deep Thing. Let's get into it. So before I show you the crazy demo and give you some really good prompts you can start using, let's go over what Gemini 3 Pro Deepthink actually is. So this is a new mode for Gemini 3 Pro that does many things different. First of all, when you give it prompts, instead of working like a normal LLM where it just thinks about one thing at a time and gives you the first answer, that's basically how every LLM works now. It does things differently. It actually explores many answers at once. So it basically creates a swarm of AIS that go and think about your prompt and your question in many different ways and this gives you significantly better results. On top of that actually refineses its answer based on that swarm of AI. So it'll get many different answers from many different AIs. Take all those answers and refine it based on which answers it thinks is the best. Again, with normal LMS, it's just giving you the first answer. There's no refinement. It thinks about your question, gives you the first answer and that's it. It is truly thinking deeply to give you the best answer it possibly can. And that is leading to really, really strong results. As you can see here, here are the benchmarks. It is basically best across the board when it comes to any sort of question answering prompt you can give it. Anything science or math-based or things that need reasoning or needs some sort of level of knowledge, it is the best. This is going to be the model you go for when you need any sort of novel results or really deep amounts of thinking. From the downside perspective, this is probably not going to be the model I use for day-to-day coding. It thinks for a really long time on every prompt you give it. So, you don't want to be going back and forth on code with it. But for any sort of question answering reasoning getting novel results, this is going to be the model you want to go with. So, when are you going to want to use this? How do you put Gemini 3 Pro Deep Think into your tool set? Well, this is what this channel specializes on, telling you when you need to use each of the AI models. So, make sure you hit subscribe below to get more insights like this. You're going to want to use it if you're doing things like complex 3D simulations. You have abstract questions that are not black and white. So, you really wanted to think deeply and come up with different creative scenarios. Science questions, again, really good at coming up with novel results. anything math, computer science related, logic task. I'm going to show you a computer science related question. Building a really awesome simulation and anything that you want a lot of different perspectives on because again, it's creating a swarm of AIS to attack your question, get many different perspectives. So things that can be looked at in many different ways, like for example, the prompt I'll be giving you later, which will help you come up with awesome ideas for building apps. So let's get into the demonstration here. First, I'll show you a mind-blowing demonstration to show you what this is capable of building. Then, I will give you a prompt that will help you come up with awesome ideas for apps you can build right away. So, to access the model, you can go to gemini.google.com. This is only unfortunately available on the ultra tier, but I'm sure very soon it will become available for the other tiers as well. But what you're going to want to do is you're going to want to go to tools and then you're going to want to go to deep think right there. The first thing we are going to build out is an advanced 3D spaceflight simulator that will show a spaceship flying around a star and have super realistic physics for that. Is this something you're going to build day-to-day? No. But this is going to show you the power of it. Then I'll show you the prompt that you'll actually be using day-to-day. So this is going to build a highlevel 3D browserbased simulator for a spaceship using 3JS. If you ever want to build your own 3D simulators, whether it's for the fun of it or you're doing something professionally, you're going to want to make sure you use 3JS from a CDN. That's going to make it super easy to build those simulations. But this is a deep prompt, which I'll put down below if you want to steal it and try this out as well, that actually defines an entire physics model, comes up with an entire architecture, and writes all the code for this advanced simulator. And the reason why this is so great for Gemini Deepthink is the fact that it is going to do tons of research all at once using multiple AIs to figure out how the physics will work, to figure out what the simulator will look like, to figure out the creativity, to put all the code together. And so it is taking this from many different angles to make sure we get the absolute best results. So I'm going to go ahead and hit send on this prompt and it is going to get to work. Here is something you need to know about Gemini 3 Pro deep thing, which they're kind of going the open AI route of having super long names, is this is going to take a while because of all the AIs it's spinning up to attack your problems and find you really good answers. It takes a while. So, you want to make sure you're only giving it prompts that don't require answers immediately. So, it's going to take a little bit of time. The way I like to think about this is I have my tools in my tool set like GPT 5.1 where I get the really quick answers there. Then I go over to my employees that are like GPT 5.1 thinking that build me a little bit more detailed plans for whatever I'm working on. Then I have my super senior deep research workers like Gemini 3 Pro deep think which we're working here which I'll go to them and say hey build me this really advanced simulation or this really advanced plan and I let them take a little bit longer to give me results. That's the key to getting the most out of AI right now is knowing which tool is the best for whatever problem you're facing and using the right tool. that'll save you the most time and get you the best results. So, it has finished thinking and here's what it did. This is actually pretty amazing. It first explains the entire physics model. So, it explains all the physics and all the math it implemented into our simulation. Even describes to us how gravity works and star mass and planet distance. It goes into all the advanced equations for the simulator, which is absolutely amazing. And then here's the good part is the code. So, we can just copy this code. And if you've never built a 3D simulator before, this is how you do it. You can go into Visual Studio Code, which is a completely free code editor, create a new project in a new file, index.html, and then you can paste in all the code it writes, and you are good to go. Then you can just open that file up, and we can run the simulation. And here we go. Here is the simulator. You can see the spaceship flying around the stars. If I actually click and drag, you can actually see all the stars in the sky and see how it's 3D. That's pretty amazing. We can change launch speeds, launch angle. So, let's reset and launch this. And you can actually play around with the physics of the spaceship flying around the star. That was all with one shot, one prompt, and it gave me all the code and actually implemented super realistic physics into that. That's amazing. Now, is this something you're going to be doing day-to-day? No. It's a really cool demo. Let's actually show you something you can use Gemini 3 Pro deep thing for dayto-day. So, here's the prompt. I'm going to go through it. how I structured it so you can get the most out of Gemini 3 Pro deep think. First of all, I'm going to go into deep think mode. And now, here is how the prompt works. This prompt, what it will do is actually give you a bunch of really good ideas for apps you can build with AI today. So, if you're anything like me, you like building things with AI. This is going to help you come up with really cool ideas based on your experience, your skill level, all of that. So, the first thing I do is I give the AI a role. you a brutally honest product strategist for solo vibe coders who don't know what to build. Your job is to generate specific realistic app ideas for solo builders that can ship, not generic start SAS nonsense, which is what the other AI really give you, not Gemini Pro deep think. Here is the person. By the way, I'm putting this prompt down below as well so you can steal it and fill it in for yourself. What you're going to do here is you're just going to fill in all the information about yourself. So you're going to put your skill level, your tech comfort, your time available, your existing audience, so I can give you marketing plans, and all the other questions here like goals around how much money you want to make. I filled that in for myself here. Then you're going to explain exactly what you want Gemini to give you uh in the response. So the idea name and a oneliner around the idea. Three to five bullets mapping out the information above the scope of the project and time to ship. The tech stack so you know exactly what tech stack you're going to use for each one of those ideas. A go to market angle so so you can have a marketing plan for all of your ideas. Risks involved with building out that project and a simple test run. So basically like your MVP, your V1 that you can build out right away. And this is a great prompt for Gemini 3 Pro deep think because it has it attacking many different things at once. It gives it very specific constraints and it has it going to hunt for novel interesting ideas for you which is what Gemini 3 Pro Deepthink is very very strong at. This is going to give us really interesting creative ideas for apps we can build. So I'm going to hit send on this and we're going to be good to go and it's going to start doing the deep thinking for us. So here we go. It came in here. We can actually see all the thinking. So, wow. It does a lot of interesting thinking with its swarm of AIs. This is a tight spot. $10,000 a month on a 1 hour a day is usually a delusion. This is what I like about it as well. It doesn't glaze you like some of the other Mazda. It doesn't make it so everything you say goes, "Oh, great idea. You're absolutely right. That's absolutely incredible." It actually is realistic with you and says, "No, that's actually not a good idea." Which is awesome. But let's see this. Okay, let's see what it's going to build out for me. So, the first idea is a rule book. So, a marketplace for cursor rules. So, a marketplace for like agent rules, whether it's clawed rules or cursor rules, that's actually a good idea. I bet you guys would actually find that useful. If I build a marketplace for clawed rules, that's actually a really good idea. So, it tells you why this is useful, scope and time to ship, the entire tech stack, the go-to market angle, so how we'll market this, and all the risks. And it gives me some other ideas as well. Repo Sensei, the context cleaner, a CLI tool or web UI that digests a GitHub repo and generates a perfectly format formatted context.ext file that allows LLM to understand the entire project. That's pretty interesting. Vibe Stack starter kits digital product disguised as SAS. So, a collection of highly opinionated preconfigured boiler plates. Okay, so like starter templates that anyone can use. I actually like that a lot, too. These are actually some good ideas. When you use AI typically and ask for creative novel ideas, the issue is that it usually gives you like AI slop. Like it gives you ideas that kind of sound good, but in reality no one would actually like. Like it just total slop. These are actually three very interesting ideas I think would be useful for the marketplace. So what I would do immediately if I was you, step one, take the prompt I gave you down below, put in your skill set, put in the information about you. You'll come up with three really good ideas you can build right now. Whether you're using anti-gravity, whether you're using clawed code, you can start building those ideas out immediately. It comes up with some really interesting novel ideas. So, here is my new tool set. Here is every model I'm using for every use case you can find. Coding, Opus 45 is still king and it is not even close. If you just want simple answers to questions, Gemini 3, current events, Gemini 3, creative writing. But here is where the pro deep thing comes in. business planning because it is super deep and actually comes up with novel ideas and results. Hyper premium model, I'm putting it in there as well since it's only available on ultra and deep research I'm using it for as well. Those are how I'm using those models. Feel free to screenshot this and use this for yourself. This is every use case I could think of when it comes to AI and which model I'd use for it. Again, the key of using AI is making sure you understand which tool you need to be using for which problem. If you learned anything at all here, make sure to leave a like down below, subscribe, turn on notifications. All I do is make incredible videos about AI. I also just launched the Vibe Coding Academy full Claude Code Master Class weekly calls with me. We have an amazing community we're building over there. Link for that is down below as well. I will see you in the next
