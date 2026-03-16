---title: "The EASIEST way to build apps with AI EVER (Google Firebase Studio)"
video_id: "ru8XPZbumNo"
youtube_url: "https://www.youtube.com/watch?v=ru8XPZbumNo"
publish_date: "2025-04-15"
duration: "12:45"
duration_seconds: 765
view_count: 29139
author: "Alex Finn"
description: |
  Build an AI tutor app with AI EASY using Google Firebase Studio!

  If you learn anything at all make sure to leave a like and subscibe!

  Follow my X: https://x.com/AlexFinnX
  Sign up for my free newsletter: https://www.1percentbetter.io/subscribe
  Check out my AI content tool: https://www.creatorbuddy.io/

  Firebase Studio: https://firebase.studio/

  0:00 What is Firebase Studio
  1:45 Prompt
  3:24 Writing Code
  4:55 V1
  6:15 Customization
  6:51 Monetization
  8:19 Adding a database
  10:50 Outro

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
    - "Google"
    - "Stripe"
    - "Box"
    - "Cursor"
    - "Lovable"
    - "v0"
  people:
    []
  products:
    - "Gemini"
    - "Cursor"
    - "Make"
  models:
    - "Gemini"
    - "Gemini 2"
concepts:
  []
summary:
  - "# The EASIEST way to build apps with AI EVER (Google Firebase Studio)

Google just released the easiest way to build apps without needing to write a single line of code ever"
keywords:
  - "ai-news"
  - "ai-tools"
  - "box"
  - "coding"
  - "cursor"
  - "frameworks"
  - "gemini"
  - "google"
  - "leadership"
  - "lovable"
  - "make"
  - "product-management"
  - "prompting"
  - "stripe"
  - "tutorials"
  - "v0"
---

# The EASIEST way to build apps with AI EVER (Google Firebase Studio)

Google just released the easiest way to build apps without needing to write a single line of code ever. If you have zero experience creating apps, Google Firebase Studio is probably the best way to build apps ever. What I'm going to show you in here is how I built this app. It's a personal AI tutor app. It's completely powered by AI. So, you can put in any subject you want and it builds you out an entire lesson plan instantly. I'm then going to show you how you can monetize it so you can start making money right off the rip and then you can put it live on the internet in just a few clicks. This is one of the coolest ways to build apps with AI ever. Let's get into it. So this is Firebase Studio. It's built by Google. You can go to studio.firebase.google.com to use this now. It is completely free. There are barely any limits on it. Google is really just trying to get people into AI. I think there's a lot of really interesting advantages to Google Firebase Studio though over apps like V0ero and Lovable. Number one, it's completely free. There really is no limits unless you start using some really premium tools they add into this. For beginners, they won't have to worry about it. Number two, it's integrated into the entire Google ecosystem. So, I'm going to show you in a second here, but if you use Gemini right out the box, you can publish it to the Android app store right out the box. You can use Firebase databases right out the box. You can host it live on Google right out the box. Really cool stuff because it's in the Google ecosystem. But let's go. Let's start building an app. So, here's the prompt I'm going with. Really, really simple. And I'll show you how to do some cool stuff right after this, including adding Stripe for monetization and a cool and a few other things. I want to build a personalized AI tutor. I should be able to enter in a subject and the AI creates a lesson plan for me and walks me through the material. This is something a lot of people are looking for right now. Personalized AI tutors. This is something you can build right now, put on the web and start selling and making money off of. Let's prototype this with AI. So, it's going in, comes up with a name for the app right away, AI Academy. I like that. Uh, it builds out the features for So, give us a little plan here, a little plan for the prototype. So, it has a lesson plan generation. Uh, it has a little AI symbol there. So, we know it's powered by AI. And this is something that's different than like V0ero is it is able to have direct integration with AI. Like with VZ, you have to go out and choose a model yourself and find the API keys. With Firebase, it's integrated with Gemini, so it has all of that built in. Generate a personalized lesson plan based on the subject that the user inputs. The lesson plan should be broken down into smaller topics. Okay, so it generates content for it. It display it even has quiz generation. So this is kind of good. This is probably powered by Gemini 2.5, I'd imagine, which is pro which is by far the most powerful AI model right now. Uh quiz generation. So, AI powered quiz generator that tests the user's understanding. That's pretty cool. That's cool. That just came up. I didn't even recommend that. And then progress tracking. Okay. So, it has Oh, I like this. I didn't really see this in VZO where it kind of goes through the style guidelines. So, the color, the layout, the typography, the icon, the animation. That's pretty cool that it just came up with that all by itself. And all I said was make a tutor. And I mean, what's cool about this is also you're learning as you go how to think like a product manager, right? How to think like a developer. These are all the things they think about. Um, so really cool to pay attention to this. Let's prototype this app. Let's get into it. Although it looks like I could have made recommended changes down there to that game plan. All right, so it's going right into it. Let's prototype the app. It's starting to write the code for us. It's doing this in Typescript. It's generating the files for the quizzes. Wow, really quick, too. This is pretty fast as compared to some others like Lovable and Vzero. Uh, really nice. What's really cool about this too again is this is integrated with all of Google's products. So, what you might be able to see here is it's going to integrate like Firebase uh automatically, which for those who don't know, Firebase is one of Google's uh database technologies. It's going to have Gemini built in right away. So, it Google's AI model, so we don't have to go off to other sites to find API keys. It's just going to do it for us and a lot of other Google's tech. This really is at the end of the day Google's advantage as it's building out all the code here is that they're an entire ecosystem around this. It's really why you should never count Google out. They're gonna have a lot of emotes just when it comes to ecosystem. Okay, it looks like it needs us to enter a Gemini API key here. For those who don't know, the API key is what allows you to connect to an AI model so you can have AI functionality in your app. This is another cool advantage of Firebase Studio is if this were any other tool, you'd have to go into another tool, sign up for a developer account, find an API key, copy it over, paste it, it'd be a lot of work. Here, I can just click on autogenerate and it'll generate me an API key in just one click, which saves me a lot of time and also means people with not a ton of knowledge of how AI works can just click a button and they'll be good to go. So, when we get to this step, if you're building along with me, just hit that autogenerate and it'll get you an API key for you. Okay, API key updated. It looks like now that that's in a the app is built out. So, let's see what we got here. Learn AI, enter a subject to learn, and then it generates a lesson plan. Okay, so let's put in a lesson plan for building AI agents. I want to learn how to build AI agents. Generate me a lesson plan. So what's happening here is it's loading a lesson plan and topic. Okay, so it's going to have the the content on the right here. And wow, look at this. So it has a bunch of different lesson plans for learning how to build AI agents. I assume this was all built with the Gemini AI API. It's a lot of letters. Let's see. Introduction AI agents. I'm going to click on that. See what we get for topic content. And then we're going to do a little bit editing here. And then we're going to monetize this. We're going to integrate a payment processor so we can make money on this as well. An AI agent is an entity that perceives its environment through sensors and acts upon that environment through actual. Okay, so it's teaching us all about AI agents. That's really sick. So it built us an entire lesson plan for us. Imag So imagine you're in school right now and you're trying to learn something. You just built your own AI tutor to learn things on one prompt. That's pretty incredible. Let's do a couple of things here. First, let's make this pretty. I got to be honest, this is kind of ugly. Don't love the way it looks. So, we're going to make it pretty. We're going to then integrate a payment processor and then we're going to host this live on the internet so other people can use it and maybe we make a couple bucks off of it. So, let's do this. All right. So, now let's do make some edits here so it looks a little prettier. Right now, I'm not in love with the color scheme and the way this looks. It looks very Windows 95. So, I'm going to give a simple command. I want to make this app look pretty. Can we give it a green and cream type colorway? I think that'd look nice. Let's see what we got here. And you can just talk to this like it's a human being. So if you want to change the colors, the functionality, anything you want, you just give it a simple command like it's an employee of yours. All right. So it has a a color scheme now. Um, let's see. Teach me about AI agents. I don't know. Maybe I didn't choose the best colors ever. Yeah, this isn't the best looking. That's fine. We I'm not Listen, I'm not a visual designer. That's fine. Oh, I I do like that teal kind of look. All right, so let's do this. Let's talk about monetization for a second. This is the number one request I get in all my videos after I show you how to build the basics of apps is how do I monetize this? How do I make it so I can start making money? I'll show you right now. I have my own app. It's called Creator Buddy. Link down below if you're interested in it. But point is is it's powered by Stripe. Stripe is a payment provider and Stripe allows you to start accepting payments for your apps. So any app you build where you want to make money, you want to integrate Stripe. So let's go back into the AI agent over here and have it put in a Stripe integration. Can you integrate Stripe here so I can start accepting payments? We'll hit enter on that. And it really is that simple. You just give it simple commands. I'm going to start building it out for you. All right. So, I gave it a simple command. Can we integrate Stripe into this so we can start accepting payments? Looks like it built out the code for that pretty quick. Okay. So, integrate Stripe. So, looks like that integrated Stripe. What you'd want to probably do from here is take the code, put it into a more advanced AI editor like a windsurf for instance or a cursor and then you can build out the advanced functionality strike. But this is a good way to get at least a prototype for it built in. One more thing I want to integrate before we put this live on the internet is I want to put some let's talk about database functionality. That's another big thing I'm asked in all my videos. How do you integrate this with the back end? So everything gets stored in a database. You can very easily do that too because this is built into Google. Google actually has a database called Firebase. So we can easily integrate that in uh which is really cool as well. I said can we now integrate a database in this to store the lesson plans? Let's integrate Firebase. I hit enter on that. Okay, looks like it is now building out the database functionality for our tutoring app. So it's building out the services. So this is the backend API. Oh, made it's it interesting. Kind of changes the looks every time we uh give it a new command, which is interesting. Oh, maybe it's a a new just kinks of being a new app. All right, builtin. Let's see what that looks like. Okay, so cool. It initializes the app. It initializes the database. And then every time a new lesson plan is created, it saves the lesson plan. So, it saves a lesson plan into into Firebase. A lesson plan saved to Firebase. That's really cool. And then when you load it up again, it gets the lesson plans. So now this has a full database functionality built in. And again, this is really cool because it's in Google's ecosystem, right? So it's built into Firebase, which is Google's database. So it again to kind of recap there. It's integrated into Gemini, which is Google's AI. It's integrated into Firebase, right? And then we can even publish this from here, which puts this on Google's hosting because it's integrated into Google's hosting. There's no other kind of AI prototyping tool. Again, I I like to think about the AI coding tools in two categories. Category one being the prototyping tools, which is Firebase Studio, what I'm showing you here, which is V0ero, which is lovable, which is really, really simple, easy to use tools to build like the kind of the prototypes to app like I just showed you. And then there's the more advanced tools like cursor and wind surf, which allows you to build out way more advanced functionality, but a little more difficult to use. Uh, but for a kind of prototyping tool like Firebase Studio, which is comparable to Vzero, it has some really cool functionality because it's integrated into everything Google. If I wanted to publish this app, I can just go through it here. I can click next. It actually builds out the hosting for me, which is really cool. I also do know it's actually integrated as well with Android. So if you're building out an Android app, you could publish this to the Android app store and put an app live from here, which again, that's the advantage Google really has is this entire ecosystem of tools. So if I wanted to go through here, put in my billing account, hit next, and then set up the environment. This is enabling the app hosting. This app will now be live in a second on the internet. And I have an entire AI tutor tool live on the internet. You know, obviously, it's not going to start making money right away. we would need to add in more of the Stripe functionality, add the payw wall, add the landing page and all that, but that isn't too difficult. It's something we'd want to do with like a windsurf for instance, but we're only a few steps away from having a pricing page now where we can start making money on this. But we have the tech built in, we have Stripe built in, we have the database built in. Now, we would just need to build out a little bit of the extra functionality to monetize it. This is really interesting. I mean, as compared to the other tools out there, like like for instance a V0, which you see here, which probably was the king of app prototypes before this, Google is pretty far along, right? I'd say it has a lot of advantages. I'd even say it might be better because of its integrations with all the other Google ecosystem with the fact that it has Gemini built in automatically. Vzero strengths, I'd say, is it's a little bit more functional. I did run into some errors with my experiments with Firebase Studio. I still think they're bu fixing the kinks a little bit with it. Vzero has been around for a lot longer, so it feels like a much smoother experience. But it's really interesting what Google has set up here with Firebase Studio because of all its integrations with other Google tools. So, if you've never built an app before, like if you don't know how to program, I'd highly recommend coming in here and trying out Firebase Studio studio.firebase.google.com. If you learned anything at all, make sure to leave a like. Make sure to hit subscribe. All I do is make really cool AI videos like this. How to build cool stuff with AI. And leave a reply down below. What would you like to see me build next? All I do is make awesome AI videos like this. But check out Firebase Studio. This is another really, really cool AI app that's come out. It seems like every day there's new AI app coming out where you can build really cool stuff. See you in the next video.
