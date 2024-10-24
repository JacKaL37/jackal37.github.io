

---

[!video](https://www.youtube.com/watch?v=hlCgJZFcc8c)


---

## Greetings!
- HEY!
- What are we doing today?
	- Making a simple webapp, maybe something about the weather. 
	- But we're doing it with AI tools throughout the entire process. 
- Around the room, calibrating, chatting: 
	- How long have you been coding, if at all?
	- Name the last AI tool you used, if any.


---

## Installation and setup

Tools:
- web browser:
	- this is our test environment for the code we're writing
	- this is also where you'll look up APIs

- IDE / text editor:
	- VSCode is the best case
	- Replit is also good! No setup. 

- AI tools:
	- VSCode extensions: 
		- Github Copilot
		- Github Copilot Chat
	- Replit has both chat and in-line predictive text enabled by default. 

- API: 
	- OpenMeteo: live weather data! 
		- no API keys, no cost
		- just keep it under 10,000 pings a day and this is a nice API to mess with whenever you need a quick stand-in

---

## A couple of simple weather apps I done made the past few days

- Quickie walkthrough of `Jacket Or Not?`
	- app page
	- code
	- the weather data involved
- Quickie walkthrough of `Weather Comparison Tool`
	- this one comes with a FULL HOUR DEMO!
	- [Full Demo - Weather Comparison App](https://youtu.be/hlCgJZFcc8c)


---

## API: OpenMeteo

- APIs are basically how apps talk to each other. 
	- You want your app to schedule google events? That's a google API. 
- Page tour: 
- Docs tour
	- Specifically highlight the *call* that is generated on that page.

---

## AI Interactions Ahead:

- Two major forms of interaction with AI tools today:
    - AI chat-- where you just have a chat in the sidebar 
    - In-line completion-- where you're typing and the AI is suggesting completions for you 
      - (this line was written with in-line completion) 
        - ((so was that parentheticl comment, but NOT this one!))
    - Both are quite handy, but they have a different feel-- one is very deliberate, one is almost automatic. 
  
### Planned Interactions
- Pre-coding:
	- Brainstorming-- pick some data about the API that you're interested in using
- Getting a base file going:
	- Quick template: chat with a model get a basic file that you can send more info to later
	- Iteration and revision: continuing to chat to work on a better version of what you're working at.
- Developing from there: 
	- Documenting / explaining:  Now that you've more or less got someone ELSE'S code (the AI's) that does something in the same ballpark as what you want, tell it to explain its code. 
	- Comment describe: prompt the in-line completion using a //comment that describes what you're looking for. 
		- e.g. "//revised version of the element above ..." or "//loop through"
	- Debugging: give the model your code and an error message and it can help fix it

### Maybes
- Things we might touch on:
	- voice-dumping
	- `system prompts`
	- "technical specifications writer"
	- test-writing
	- documentation-writing
	- translating code between languages

---

## ASIDE: Basic webdev pattern
- Save the code
	- CTRL/CMD + S in your IDE -> writes the file to the disk and lets you run it in its current state
- Run the code
	- first time: `open` the html file locally in your web browser
	- after that, just `refresh` the page with `ctrl/cmd + R`
- iterate!
	- Build a bit, check to see if it works

simple web dev world: 
- open your browser
- pop open the inspector:
	- right click the page > inspect
	- `ctrl/cmd + shift + I` or `F12`
- `inspector` tab:
	- check on the `html` structure on the page, edit it, do whatever
	- you can highlight elements
	- and clicking on them, you can see the `css` applied to that element
- `console` tab:
	- check for outputs from your `console.log()` calls-- things you print out yourself
	- `errors` -- if your code breaks, it explains it here.
		- line number, error name, stack trace
		- ^ INCREDIBLE data for the AI to get its hands on ^
	- also lets you enter `javascript` commands on the fly to test ideas

--- 

## Active Demo Time!

Let's build something together!

I suggest we hash it out like this: 
- I'll do some things
- You try them at home.
- We chat about it. 

You can follow super closely to what I'm doing, or you can choose your own adventure.
- But keep it closer to simple for the sake of this precious 90 minutes together. 


---

## AI Pattern: Brainstorming with Chat
- Maybe all you came up with was a vague goal-- "let me do something with "
- A `brainstorming` chat pattern has you and the model *discussing* what you're working on. 
- Outcome: varies, but likely a basic sketch / outline of whatever you're designing. 
	- Advanced: If you want some legitimate system specs, you can ask it to write a `technical requirements document`

Now that the idea is a bit more fleshed out...

---

## AI Pattern: Quick Draft with Chat
- Once you have an idea cooked up, in the same chat, you can ask it to write up a basic draft of the concept. 
	- Things like ""
- Let's get a basic scaffolding going just using copilot
	- Yeah, you can totally do this yourself, but let's futz with copilot to make the basic html template for our app

- Now a gut check: test the file-- how good is this?
  - Great! -- then we can take it and move on!
  - Good, but I have revisions -- also good, you can iterate with the AI
  - Awful -- might be best to restart with a fresh chat if it feels like it's totally busted

---

## AI Pattern: Iteration and Revision

- Once you have a file, but it's not quite right, you can keep the ball rolling by asking for revisions. 
  - Because it has your whole chat so far, AND the "bad" version, it will have a very strong grasp of what you're doing (usually)

- When iterating with the AI, you want to ask it for *substantial changes*. 
- If it's something like "make it pink"
  - you can just ASK it what to change, don't make it rewrite the whole file
- IF it's something more like "can we rework the design to use more whitespace?"
  - That's a fairly big ask, and worth the full rewrite

---

## AI Pattern: Documenting code (in-line or chat)

The AI is going to 


---

## AI Pattern: Comment Describing with In-line Completion


---

## Debugging


---
