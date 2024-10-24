

## Greetings!
- HEY!
- What are we doing today?
	- Making a simple webapp, maybe something about the weather. 
	- But we're doing it with AI tools throughout the entire process. 
- Around the room: 
	- How long you been coding, if at all?
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

---

