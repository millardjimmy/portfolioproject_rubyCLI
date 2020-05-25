Introduction


The upcoming CLI project is a great chance for you to show off everything you’ve learned about Ruby so far and for many of us, make the first app that's all your own! This lesson is provided to help you tackle your first portfolio project. Tips on all aspects of the project are included here, so make sure to have a look through!

Use this lesson to help you help you plan for your CLI Project

Note: Keep in mind that the Ask a Question is not permitted to help while you are building your projects. Use the internet and the resources provided in this document if you get stuck!

How to Get Started On a Successful Project Build
The next lesson includes the project requirements for this project. Read through the requirements carefully before getting started.

Come up with a project idea of your own, and devote some time to a planning session. Think about the following:

a. What will your app do? What is the user experience? b. Where will get your data from? (This might be a website that you will scrape or if you prefer, an API.) c. What will you need to do with the data once you have got it? d. What classes will you be using? e. How will you display data one level deep to the user?

Check out the sections below on User Story and Flow Diagrams.

Create a skeleton app and repository on Github. Here is a video that walks through how to do this. For more insight on how to plan out and get your project idea off the ground, you can watch this live build, which also shows how to use our Scraper Checker tool.

Plan your schedule. Note that it takes most full time (40+ hrs/week) students between 3-7 days to complete, and can take up to 5 business days to schedule your project review after that.

Join the Slack channel #cli-data-gem-project to connect with others who are working on their projects as well. Students often set up a peer review in advance of their project review as a way to practice talking through your code.

We are here to help! Each week, there are Open Office Hour study groups specifically designed to help with CLI project questions. Keep an eye out also for our OO Ruby study groups, What To Expect In Your First Project Review and the Live Coding Club.

Making a User Story
Who is your User?
What is their pain point?
How do they use our soluiton to overcome this problem?
Example: Gemma has dietary requirements which means that she can’t eat gluten or dairy. Her friends have invited her to dinner at the most excellent pizzeria Zozo. Her WiFi connection is a bit patchy and the graphic-heavy Zozo website is not loading - all she wants is to know what allergens are in the dishes! Now she can use the Zozo Menu CLI App:

She starts the app and is greeted with a list of dishes on the Zozo menu
She chooses a dish and is shown the allergens in that dish
She can then either go back to the list and choose another dish or exit the app
Choosing Your Classes
If this was a human-run business, what roles would I be hiring?
What responsibilities would they have?
Let’s take the Zozo Menu CLI App we’re building for Gemma. If this was a human-run service we may need:

A customer service specialist:

Responsible for asking Gemma questions and delivering her the answers.
An in-house expert on each of the MenuItems

Responsible for holding the information the runner has gone out to get. Our runner will complain if we ask them to go and get info they already retrieved!
A ‘runner’:

Responsible for going out into the world and getting data from the Zozo website when our in-house expert needs to know
In the Zozo app, these might be called CLI, MenuItem, Scraper.

Making an app flow diagram
How is data passed around your app?
What classes are used? What are their responsibilities?
How can I avoid unnecessary duplication of actions?
We recommend using draw.io to put together a flow diagram. It doesn’t need to be over-complicated - just a visual idea of your app’s structure.

H

You don’t have to use software for this - a photo of a (legible) hand-drawn sketch on a napkin also works! The symbols used in the examples above follow basic flowchart conventions. If you’re interested in learning more, here is a great overview.

Please make sure the image or file you share with us is accessible. 

