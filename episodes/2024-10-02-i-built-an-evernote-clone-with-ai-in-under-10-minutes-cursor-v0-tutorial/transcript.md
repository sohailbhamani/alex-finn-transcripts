---title: "I Built an Evernote Clone With AI in Under 10 minutes (Cursor + v0 tutorial)"
video_id: "-oU59HJ7POc"
youtube_url: "https://www.youtube.com/watch?v=-oU59HJ7POc"
publish_date: "2024-10-02"
duration: "12:59"
duration_seconds: 779
view_count: 4132
author: "Alex Finn"
description: |
  Follow my X: https://x.com/AlexFinnX
  Subscribe to my newsletter: https://www.1percentbetter.io/subscribe

  Learn how to build an Evernote clone with AI! No programming experience necessary! Beginner friendly! We use Cursor, V0, and the ChatGPT API to build an Evernote clone in under 10 minutes. You can then use these skills to build any application or game you want.

  Timestamps:
  0:00 Intro
  0:40 v0
  1:43 Cursor
  1:59 Install NextJS
  2:24 Install Component
  4:31 Add new note
  6:00 Add rich text editing
  8:27 Implementing search
  9:30 ChatGPT API
  11:47 Final Product

  Commands:
  bunx create-next-app .
  npm run dev

  Cursor: https://www.cursor.com/
  ChatGPT API: https://platform.openai.com/docs/api-reference

yt_tags:
  []



# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Tools"
difficulty: "Intermediate"
audience:
  - "Engineers"
  - "Product Managers"
entities:
  companies:
    - "Cursor"
    - "YouTube"
    - "v0"
  people:
    []
  products:
    - "Cursor"
    - "Make"
  models:
    []
concepts:
  []
summary:
  []
keywords:
  - "ai-tools"
  - "career"
  - "coding"
  - "cursor"
  - "make"
  - "product-management"
  - "prompting"
  - "tutorials"
  - "v0"
  - "youtube"
---

# I Built an Evernote Clone With AI in Under 10 minutes (Cursor + v0 tutorial)

I am sick and tired of paying for Evernote in fact I'm sick and tired of paying for all software we are here today going to build an Evernote clone using Ai No coding necessary no technical skills necessary by the end of this video you'll have your own Evernote that you don't have to pay for anymore will be completely built by yourself you won't write a single line of code and you'll be really proud of it you'll have your own app that you built here's the coolest part it's going to be AI powered we're going to connect it to chat GPT so you can sumarize your notes and do a whole bunch of other cool AI stuff here's the plan I'm going to build the UI up using v0 and then I'm going to build the functionality out using cursor both are no code AI tools so here I am in v0 this is just v.d completely free I put in this prompt to build out the UI I want to build an Evernote type note taking app on the left hand side will be a sidebar that has a list of tags in the middle area will be a list of notes the notes will be displayed as cards the cards show a preview of the notes and show the tags when you click on a note an editor pops up in the mle that makes up most of the takes up most of the screen this is where you can edit the note I'm just telling the AI exactly what I want to build it's going to build me out the UI no coding at all we hit enter on this and this is the UI it spits out I didn't do anything it just spits this out for me now we can start building out the functionality this is really sick you have your tags you have your notes I can click edit I can say this is a new note I can click save boom I have a new note how sick is that now let's build the functionality out in cursor by the way I highly recommend you do this all along with me download cursor go on v.d all the links are down below follow along with me build with me you'll have your own app let's go this is cursor this is the most powerful AI tool I've ever used you can build apps just with AI prompts no coding at all link down below if you want to download I'm opening up a new folder to put the app in what I'm going to do here is I'm going to hit control till day to open up the terminal follow along with me here I'm going to install nextjs which is the technology that's going to power our app I'm going to do bun create next- app space period hit enter then you're going to do the default options for each option they give you that's going to build out the next app now your text good to go what we're going to do in a second is actually install the UI component we just built from here we go back into v0 we're going to grab our UI we're going to hit this button up here add to codebase we're going to hit the copy button right there we're going to go back into cursor boom we're back into cursor we come into here we paste that command in we hit enter that bad boy is going to get installed very very easily we haven't ritten any code so far we hit yes and the default stuff for all that just like that that's installed now all we need to do is go and make sure it's implemented into our app follow along closer it's easy but follow along I go into Source app page we're in here see this return statement this is everything that's going to be displayed on your screen let's get rid of it all we don't want any of this default stuff I go down here I delete all that now we just have this normal return statement let's do this we enter a fragment which is just these little arrow keys right there boom do that now we're going to put in our new component that is called note app component so we're going to do this we have our fragment we do another one note app component it autofills for us look at that just like that it was all autofilled make sure what you have matches up to what I have here also make sure that the name of the component you put in there matches what you have in the new component you just installed so it' be export function and that's the name of your component right there that needs to match up to this if you do that you're good to go so now let's run the app here we go I want to see what this app looks like go into your terminal type in npm runev hit command s or controls to save it so you're good to go then you hit npm runev you hit ENT it's going to run it for us let's see what this bad boy looks like I click on the address let's pull it open here come on baby come on Boom there it is look how beautiful that is look at look how beautiful that is you got your notes you got your tags it looks exactly you have your own app just like listen we're going to do a lot more we're going to add a whole bunch more functional this is going to be super sick but you up to this point have built your own note taking app that's pretty sick but let's add a ton of stuff to this first I'm looking at this we need to add an add note function there's no way to add a new note let's add that I'm going to show you how to build this with AI very very easily come back in here hit command shift I to open up your composer let's do this on the screen so I can add a new one very easy plain English I need to add a new note give me a new note we're not writing code this is very simple I'm just doing it in plain English I hit enter it's going to start writing the code look at that boom boom boom all the code coming out for us I didn't need to do anything special here it writes the code uh we can look to add new add new but we'll need to modify the note component here's how we update the Note it writes the code it tells us what it's going to do I hit accept before I show you this next piece of functionality if you've learned anything so far make sure to hit subscribe turn on notifications hit the like button and then let me know in the replies what other apps you're paying for currently I'm going to show you how to build them all these videos are based on user feedback so let me know what other apps you're paying for I'm going to build them out in next video so you don't have to pay for them anymore I want to save a little bit of money let's see what we got here oh look at that add new note look at that beautiful a good-look button I click it new note we can go in edit it wow this is a new note wow subscribe to Alex unbelievable hit save there it is it's saved we're making our own notes this is sick let's do some cool things here I want to be able to make this like a rich text edit I want to get a whole bunch of options here let's do this let's make this rich I want to be able to do bold italic styling colors things like that we want to make our notes pretty let's go back in here we back into cursor let's go back into the composer I want to make the text editor in the notes a rich text editor so I can do bold and styling one sentence I'm hitting enter it's going to implement it for me all right to implement a rich text editor for your notes we can use the react quill Library okay so it's telling us to it's telling us to install this new library we're going to do that it's writing all the code for us look at all this code this would take hours if I was developer they I like I got this for you bro I hate accept all boom let's let's install this new library so I copy it from the composer I paste it into the terminal I hit enter it installs it for me I just got little AI buddies doing everything for me over here that's installed pop open the note taking app to see if it's a rich text editor now I'm going to add a new note let's edit that oh boom look at that new note hit the like button let's go in here let's see if we can make some pretty things this is a new note let's see can I bold it boom I can italicize it I can underline it I can strike it through I can do bullet points I can add images this is beautiful now let's just make this text area a little bit bigger I want to make this a little bit bigger so I can see multiple lines little error handling for you guys here let's do this I go back into the composer just again just like it's English let's go in here I want to make it so there is more area seen in in the Rich Text Editor at the moment I can only see one line in the editor enter it's going to fix that for us you need things fixed you need styling changed you just go in here you let it know what it's doing it fixes it for you the lines of code are being written it's going in I accept all we go back into our app I hit edit boom now I got the whole line turn on notifications look at this boom let's see here we can make oh we can number it we can indent it we can add images let's see let's see what happens when we add an image it's my last video no code Call of Duty if you want to check that oh image in there that's looking beautiful I hit save oh you can see the image gorgeous why would I ever pay for Evernote again let's add a couple more features I want to have the ability to search my notes I want to be able to go in here search and find the notes I want so let's do this let's go back into our composer so this is the prompt I'm putting in I want to have the ability to search my notes give me a search bar at the top so I can type in and dynamically find my relevant notes I want like a really good search bar I don't want an average search bar I want a really good search bar here we go it's building out all the code for me too easy I don't even know what any of this means it's just building it out I hit accept all thank you AI thank you AI for doing this all for me I go back in we have a search bar let's create a couple notes reply to the video give me feedback we hit save so we got three notes here let's search for them let's say feedback oh look at that it's dynamically filtering the notes feedback something like that take hours for a developer to build I just did that what that under a minute unbelievable why would I pay for a note- taking app ever again why would I pay I got tags I can edit things I can make them look pretty I can search why would anyone pay for a note taking app again I did this in like under 10 minutes I built an entire note taking app all right let's add the coolest feature yet I want to be able to hit a button and then AI summarizes every note I've taken we're going to do this with the chat gpta API it's going to be super cool follow along here there's no one else on YouTube doing this you're going to see something really really cool here so watch this so let's go back into the AI let's implement the chat GPT API basically what the chat GPT API allows me to do is through our app send prompts to chat GPT and it sends information back so I can send the chat GPT here's all my notes Give me a summary and it sends back a summary so let's do this so we're going to go to the composer again and we're going to have it implement the chat GPT API so I'm going to tell the composer I want to connect my app to the chat GPT API I wanted to I have a button that says summarize notes and it sends back a summary of all my notes from the API enter here we go come on AI build something cool for us here here we go all right to add a summarized notes feature using the chat GPT API will need to make a few changes to your note okay so it's going to add the button it's going to create the API call we're just going to need to install open a I which will do let's hit accept all now what I'm going to show you how to do is how to get your chat GPT API information so follow along closely here we need our API key so what we're going to do is we're going to get it from the developer dashboard go to platform. open.com sign up through there if you haven't already then what we're going to do is go to dashboard API keys from here you're going to click create new secret key I'm going to call it evern AI clone create the secret key this is going to give you a secret key just copy that and then you go back in here we're going to create a new file called EnV we're going to put in this new command here in EnV and now we just need to put in our API key so get that copied API key and put it right here and paste it now just make sure to install open AI with that Command right there in the terminal boom hit enter we're getting an error on these two variables up here so let's just go into the composer and fix that I'm getting an error in summarize on the configuration and open AI Imports so we hit enter on that it should fix that for us boom just like that it's fixed I hit accept let's go back into our app let's see if we got cool AI functionality here let's summarize these notes holy crap look at that wow summary the first note is a welcome message for a new note taking out the second note contains a list of project ideas all right let's add a couple notes and test this out what you need to do let's go in here subscribe turn on notifications like leave a reply we hit save let's do another one add a new note what I want to eat for dinner I want to eat steak creamed spinach chocolate lava cake all right let's see what this does let's summarize these notes now this is how sick is this so we're going to hit summarize no okay here we go uh instructions what to do subscribe turn notifications likely reply and then the list of dinner options I don't even think Evernote does that we just built a product better than Evernote for free by ourselves without writing a line of code holy hell that's amazing you can take these skills from here and build out literally anything you want anything if you learned anything make sure toit subscribe make sure turn on notifications hit the like button let me know down below what other apps you're paying for I want to build them out for you see you in the next video
