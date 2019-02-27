# SaaS Application Development



The first thing to note here is that books are written linearly and the production of SaaS systems are not. Your development team should have started around the same time your UX designer was wrapping up the first three quarters of their work or so, give or take some. They would have had enough information at that point to at least get going on a number of systems and depending on what your SaaS system/business does, they may have gotten started before your designer ever started asking their questions.  


### Your SaaS MVP Pre-Development Build Checklist:

Before you get started, you should have most or all of the following items completed. This list does NOT include any of the marketing tasks, just system build tasks. [Marketing and traction is covered in the marketing, sales, and traction chapter.](https://docs.google.com/document/d/1qLCH0YaNhxbutZeK9Oo87n9PhssDaHLkWLTPYW0UIMQ/edit#heading=h.ihvpvx62eeam)  
  


| TO DO | CHECK IF DONE |
| :--- | :--- |
| Project is validated and you are 100% sure people want to buy it so much they have already pre-purchased it |  |
| Have researched major groups of users, know what features they want, and have determined what value metric you’re using |  |
| Different plans and their costs figured out |  |
| Pricing page is planned out |  |
| Team is selected |  |
| Tech stack decided |  |
| Project management system is selected and team has been informed on how to use the tool. |  |
| Project plan written, approved, and accepted by all team members and stakeholders |  |
| Information architecture written |  |
| Your documentation system is planned and prepared |  |
| Admin panel data-management needs outlined and planned |  |
| Payment system chosen, accounts set up, and bank accounts connected |  |
| Unit testing system chosen and integration planned |  |
| User processes generally planned |  |
| System transactional emails planned and designed |  |
| User flows designed |  |
| Page designs and views created and agreed upon |  |
| Integrations with other systems generally planned out |  |
| Initial user tagging and triggers planned |  |
| 3rd party systems to be built into your system considered and planned |  |
| Development environment is set up |  |
| Code repository system is selected and a repo is set up |  |
| Remote systems deployments prepared |  |
| Automations server for continuous integrations is selected and planned for deployment |  |
| Dependency and systems costs generally planned |  |
| 3rd party systems costs planned |  |
| System build labor costs estimated |  |
| Operational labor costs estimated |  |
| Initial marketing & advertising costs determined |  |
| All initial costs have been funded and ongoing costs planned or funded |  |
| You’re feeling good about this? |  |

#### Let’s talk about ‘Sunk Costs’

Before we get started, I think it’s an important time to discuss my projects that got to this point and never got off the ground. More than anything, we need to talk about the concept of ‘Sunk Costs’. If you think back to your Accounting 101 class in high school or college, this may sound familiar to you.  


According to AccountingTools.com, a ‘sunk cost’ is:

A cost that an entity has incurred, and which it can no longer recover by any means. Sunk costs should not be considered when making the decision to continue investing in an ongoing project, since these costs cannot be recovered.

What this means to you is that just because you spent all this money and time getting this thing ready to go doesn’t mean doing it is the right choice. This is also known as the “Sunk Cost Fallacy”. The misconception is that you make rational decisions based on the future value of investments and experiences. The truth is that your decisions are tainted by the emotional investments you accumulate, and the more you invest in something the harder it becomes to abandon it.  


To illustrate this, let’s take a look at my personal projects that did and didn’t get started at or before this point:  


Started but didn’t finish

* Incentivs - sales gamification, just like what is now Ambition.com
* Dogwalkit - pretty much just like Rover.com.
* Leadbutton - lead gen system

Started and failed

* RIS - practice management system for diagnostics imaging
* The GuideFor Platform - ratings and reviews system for specific industries
* Guide for Seniors - Content platform for seniors and the caretakers of US senior citizens

Started and Growing

* Map Dynamics - Web-based mapping, agenda management, and sales system for trade shows, focused on associations.
* BrainLeaf - Project scoping, approval management, digital signatures, and financial reporting tool for digital agencies. We use this extensively at my agency, JHMG, so it is always growing.
* Medrev - Reputation management for larger healthcare groups, outpatient care, and hospitals. Just getting started, but looking good so far.
* Diagnostics Marketing - Marketing platform and productized services company for diagnostics imaging

Right now, we’re running 4 for 10. Not great -- or so it seems. What is important to note here is that I got started, realized I didn’t have some aspect of something I needed to do the project, and abandoned it. In most of these cases, had I gone forward, I would have failed. But I didn’t realize it until I did some or most of my planning and actually got going on the project.  


PROTIP: If you don’t feel good about it, don’t do it. You’ll probably just be throwing your money away anyway.

The application build process should only be started in you have done all of your planning. I want to say it again for you so you don’t waste your money and time: THE APPLICATION BUILD PROCESS SHOULD ONLY BE STARTED IF YOU HAVE DONE ALL OF YOUR PLANNING. So don’t stop here and start building; read the rest of the book first.  


Okay, then. Let’s build this thing.  


### Developers

#### Brain surgeons \(neurosurgeons\) and skin doctors \(dermatologists\)

Doctors make for a good analogy for developers. Doctors get an in-depth study of medicine in medical school, then do a deep dive study for several years known as a residency, in their specialty. In day-to-day work most doctors practice only their practice their specialty. They understand what other doctors are doing, but since they don’t do it all the time, and only studied it superficially, they don’t know the in’s and out’s of other specialties.  


In an emergency, could they get by? Probably? Maybe? How about ‘most of the time’?  


But I certainly wouldn’t want my dermatologist operating on my brain. That would be a terrible idea! The dermatologist has never done brain surgery. She might have an idea where to start or where to go, but there is a big difference between a brain surgeon and a dermatologist.  


On the flip side, you probably don’t want your brain surgeon working on your face. He might know all the nerves in your face really, really well, but what medication is the right one for your acne given all the variables in your life? That is in a totally different realm than what she deals with every day.  


#### Types of Developers

The world of software development is similar to this. Different developers focus on different things. There is overlap, but there is always going to be a relative advantage in one area vs. another.  


Generally, developers can be broken up into two different major areas or specialties when it comes to cloud SaaS development.  


If you are a developer reading this list, please remember this is an overview, not an in-depth study. The goal is to help people understand what kind of variety there is in development, not to delve into the aspects of these systems or to define any overlap.  


These are the areas of development and some of what they encompass.  


* Frontend Development - Make things look and work well for users across the spectrum of devices.
  * HTML
  * CSS
  * JS
* Backend Development - Make things function and build logic.
  * PHP
  * ASP
  * PYTHON
  * NODE.JS
  * Angular.JS
  * Java
  * Lots and lots of other languages
* Mobile App Development - Focuses on the development of Android, iOS, and hybrid apps.
  * React.js
  * Ionic
  * Phonegap
  * Swift
  * Objective C
  * C\#
  * C++
  * Java
* Database Development - Store the data, retrieve the data, make the storage and retrieval as efficient as possible.
  * SQL
  * MsSQL
  * MySQL
  * PostgreSQL
  * Mongo DB
  * Loads of other database systems
* DevOps / SysAdmin - Sets up and manages your hosting environments and troubleshoots issues as they pop up.
  * AWS
  * DO
  * Apache
  * Nginx
  * SQS
  * Lambda
  * Ansible
* AI
  * R
  * Python
  * Lisp
  * Prolog
  * Java

Think of each of these systems as a language that you could speak. If you know English, you could probably learn Spanish easier than Russian or Thai. The alphabet is the same, the verbs have similar kinds of conjugations, etc. But it is still a different language and you’d need time to learn it. Also, to be conversational is necessary to have a conversation, but if you want to write a book in it, you’ll need to be fluent. The same is basically true for computer languages.

#### The myth of the ‘Full Stack Developer’

You may have heard of the ‘Full Stack Developer’. This is someone who has knowledge of all the layers in a system. A lot of people call themselves Full Stack Developers, and some really are, but most are not. No matter how good you are at the different areas, you are still going to have a specialty in one over the over. You simply cannot devote your life to learning two things and, all other things being equal, be as good as someone who has devoted their life to learning one thing. There is ALWAYS a relative advantage in one place or another.  


In this book we break developers into just front-end and back-end developers, since very often, this is how developers think of themselves and where their specialties lie.  


### Development Time Increases As Complexity Increases

When you think about it, it makes perfect sense. The problems are that: 1\) most people don’t think about this; and 2\) most people don’t consider by how much complexity increases in projects. These two issues can cause some serious issues in planning and build if they are not considered.  


#### A quadratic increase in time

Sounds complicated, doesn’t it? It’s not really though. Let’s walk through this:

1. If you have 2 features that send data to and from each other, you have an in and out connection each way. So that is 4 connections of data.
2. If you have 3 features, then you have 12 connections.
3. At 4 features, if all features have to connect to one another, then you are at 24 connections.
4. If we skip 5 and move up to 6, now we are at 60 connections!

Each one of these different connections generally has some kind of graphical or interactive representation, but no matter, they all have to be checked.  


Let’s make it simple and say that each item takes 10 minutes to check and there is and issue with one in every 10 items that takes an hour to fix. If you had two features, the system would take you an easy 40 minutes to check and according to our formula, probably no issues to fix. But if we took it to a six feature project, now we are looking at 10 hours to check everything and 60 hours \(you didn’t read that wrong, it is 60!\) to fix the problems, and that is a very simple model!  


If, when you are planning the build time of the system, you plan only the build of the features and not an extra level of time for a thorough debugging and review, you are going to underestimate your build, your costs, your time to market, and generally just be very upset.  


But now you know, and you won’t make this mistake, right?

### Development is Iterative

Development follows a path, but is, at the core, an iterative process. It almost never happens that a developer gets something perfectly right the first time they do it. Development is testing and testing is development. This is a misconception I’ve seen many times over the years. Clients think that testing can be skipped or skimped on, but it is a part of the development process and any cutting back on this means that the system will be incomplete.  


Additionally, the improvement of systems is iterative. The best set of features that can be built within the given amount of time is built, promoted, sold, and then reviewed for customer feedback and iterated on in the next release. For more information on the general process, take a look at the chapter on [Continuous Integration.](https://docs.google.com/document/d/1qLCH0YaNhxbutZeK9Oo87n9PhssDaHLkWLTPYW0UIMQ/edit#heading=h.18qyyg22zu05)

### Front-End Development

#### Front-End Developer Tasks

Front-end development generally refers to the coding of the systems you see. This means the code that delivers the content from the back-end systems to the user. The front-end developer takes the designs that were done and turns them into views.  


Very often, especially nowadays, there is overlap between front-end and back-end for front-end developers because in order to see the data in a meaningful way the front-end developers benefit from being able to tap into the data to deliver information.  


What this often means for SaaS development is that your front-end developer can take the designs your designer did and turn them into something you can click through and load as a web page, even if there is no functionality behind them. By this, what I mean is that the front-end developer could make the view of a calculator, but when the user clicks on the buttons, nothing would happen. Really, they could do more than this, but this is just an example.  


#### Starting up Front-End development

When your designs are done, I mean really done, with everything thought out. It’s time to give them to your front-end developer. This developer can work in parallel with back-end development, but since the book has to be written linearly, we’re starting here.  


What the front-end developer needs to do their job:

* Information Architecture with explanations of features, pages, elements, etc.
* Content - this is the text that goes on the page
* Wireframes and/or Flows so they can see what the page should look like
* Style guide - so they know what different features should always look like and have consistency.
* Project Plan - This is a set of deadlines and explanations of who will have what done when that the other team members need to progress. Remember, developers are optimists! Give them deadlines, but plan on them missing the deadlines by at least 20%. Project deadlines are set up as part of the Project Plan. More on this in the [Managing your team section](https://docs.google.com/document/d/1qLCH0YaNhxbutZeK9Oo87n9PhssDaHLkWLTPYW0UIMQ/edit#heading=h.xm6ncpqqem9h).
* Management - With multiple team members doing different kinds of jobs and relying on one another, even the most experienced and responsible developer benefits greatly from help getting what they need from other team members and coordinating timelines so they are not waiting.
* Regular Meetings & Communication - Even if everything is planned perfectly, there will be questions and things will change.

The more information a front-end developer has, the less they will come back to you with questions. This is where the flows, designs, and information architecture come in. The front-end developer will take these pieces of information and develop pages and views from this information and deliver them to you for review and revisions.  


To make a front-end code change often takes a lot longer than making a change in a graphics editing system, like the one your UX designer is working with. So do all your designs there before getting into coding. In addition, making logic changes have far reaching effects, so make sure you’re happy with the system the front-end developer is doing BEFORE you hand it over to the back-end developer.  


PROTIP: At each step down the process, the cost of making changes goes up. So get as much as possible finalized before coding begins. Changes during coding can crush an MVP build budget!

### Back-End development

#### What the Back-End Developer Does

In a SaaS build, especially for an MVP, the back-end developer will generally figure your best setup for a serving platform, get the environment setup, and code the system. If your SaaS requires different kinds of developers, different back-end developers will have different responsibilities. If your system is an app or has an app portion, you may need additional developers with specialties in those technologies as well as developers with web-app building specialities. Or, if you have an AI component, you may need an AI specialist who just focuses on that portion of the project.

PROTIP: If your SaaS has an app component, most of the time you will also have a web-app component for managing users and data.

#### Starting Up the Back-End Development

More than likely, actual back-end development got started well before you got to this point. The back-end developers had to set up the environments & platforms, pull in dependencies, figure out what systems would be used, plan the database, figure out what systems need to be integrated, and much more. All of this work takes time. Unless they have built the same or a very similar system in the past, they have days of work and research to do in order to get ready to do their primary jobs. Some of these tasks won’t be done until the team gets to the point where they are ready to check off that particular item on the list, but much of the work can be done ahead of time -- and the more that is done up front, the more accurate your time and financial estimates will be.  


PROTIP: The key to accurately estimating hours is to have your team break things apart as much as possible and estimate hours granularly. For more information on how to do this, take a look at the BrainLeaf.com website at the book “The Comprehensive Guide to Website Design, Web-app & Development Project Scoping.”

What the back-end developer needs to do their job:

* Information Architecture - with explanations of features, pages, elements, etc.
* Wireframes and/or Flows so they can see what the page should look like
* Coded Style Guide - so they know what different features should look like and they have the front-end code done before implementing.
* Pages, views, and states coded and ready for development
* All back-end systems finalized
* Project Plan - This is a set of deadlines and explanations of who will have what done when that the other team members need to progress. Remember, developers are optimists! Give them deadlines, but plan on them missing the deadlines by at least 20%. Project deadlines are set up as part of the Project Plan. More on this in the [Managing your team section](https://docs.google.com/document/d/1qLCH0YaNhxbutZeK9Oo87n9PhssDaHLkWLTPYW0UIMQ/edit#heading=h.xm6ncpqqem9h).
* Management - With multiple team members doing different kinds of jobs and relying on one another, even the most experienced and responsible developer benefits greatly from help getting what they need from other team members and coordinating timelines so they are not waiting.
* Regular Meetings & Communication - Even if everything is planned perfectly, there will be questions and things will change. This is a cornerstone aspect of Agile Development Method.

### Quality Assurance \(QA\)

QA is the place in the project that so many people falter. Entrepreneurs getting to this point often don’t realize what goes into it and thus underestimate the time it takes to do this, and both developers and project managers get to this point around the time they are getting tired on the project MVP or release. So understanding the amount of work and time it takes to get a project ready for release is critical to creating a solid user-ready system.    


Digging deep into the project from multiple perspectives is key to a good release, whether it is your MVP or a new feature in a mature system. When doing QA, especially for a new system, it is critical to have multiple people looking at the system from different perspectives. Designers will see issues with the user experience or flow, final system users will see different aspects of use that could be improved upon or sometimes need to be fixed before the system can be used, and of course developers will see development issues.  


#### QA Lessons:

1. Realise that QA is an ongoing process, not a one time project

Entrepreneurs I’ve met so often think their QA will be ‘done’ at some point, despite the fact that they have more development coming. It doesn’t end. QA is a part of development and as long as you’re building complex systems that interact with each other, you’re going to have to do more QA to get a good product. In fact, there is a very clear correlation between the amount of QA time spent on a project and how well the launch goes.

2. Have a separate QA team or developer

Having been a developer, a project manager, a tester, and a SaaS entrepreneur, I can tell you that when you’re building something, you just don’t see the bugs sometimes. You can go through the whole thing and test it yourself and not find any issues only to have one outsider look for five minutes and a see major issues right away. Even the best developers don’t see the issues in front of them when their heads are in the project. So, always, always, always have someone other than the lead dev or dev team doing QA on your project or you are going to have things slip by.

3. QA from different perspectives

On my projects, I like to have a QA engineer, UX designer, developer, and project manager run through a set of tests before the project is ready to launch. It is time consuming and often very frustrating, but it is worth every second. Each user type sees things that the others don’t, and having them review the system can give you feedback that you would otherwise never have had. That being said, have the lead QA person do the review first and fix the first round of bugs before having everyone else go through the system or a lot of time will be wasted.

4. Writing descriptions of bugs technically and thoroughly saves a lot of time

Everyone on the development team, entrepreneurs, designers, and other stakeholders especially should have at least some amount of training on how to technically explain bugs in the system.  


A lot of time can be wasted by developers searching for bugs that either don’t exist, aren’t bugs, or are not relevant. Well written bugs can probably save 7% - 20% of time in debugging.

5. Write specs and tests

Specs and tests are a part of Agile Methodology. When writing a specification for work, if you write out how to test that specification it will streamline how QA team members test the system. This can be more challenging on an MVP, but as the system progresses, it becomes critical.

6. Use an industrial strength PM system when doing technical QA

Using a sub-par system to track and manage bugs is can be a point of failure for the development of a system. My personal preference is JIRA with their integration into BitBucket and Confluence, but there are of course other systems out there. If you don’t have an industry standard system in place for this, you and your team will start losing bugs, or prioritizing issues incorrectly. So get the right tools and know how to use them!

7. Spend the time now or triple the time later

Technically speaking, you don’t have to do a round of QA. If you don’t though, you’re going to have a product that doesn’t work and people get upset about. If you do a halfway job of QA prior to launch, you’re going to have half-way or less happy users. This is invariably going to lead to you or your team fixing the issues later and now having to deal with a bunch of upset people and a failing product.

8. Assessing QA time

Quality Assurance in a SaaS business generally takes anywhere between 10% and 25% of the time to build the system. It never, ever takes less than 10%, so make sure to account for that in your timelines!

9. Padding your Expectations

When building SaaS systems, as an entrepreneur it is important to pad your expectations when it comes to the QA process. Really, you should pad your expectations throughout the entire project and you’ll be much happier, but, at the very least, do it here. If the team tells you it is going to take 2 weeks to QA the product, just plan on 4 weeks of work. It may sound outrageous, but that’s almost exactly the way it goes almost every time. If you’re working with an agency that is already taking this padding into account, then I would suggestion you still pad this timeline, just not by as much.

Storytime with Jason: Don’t Send Me Shit Work or I’ll Just Send It Back

It was the first time I was looking over the system and within a minute I had already found a handful of critical bugs and was getting frustrated. “Why would you even send me this to review?!” I was fuming to myself.  


“This is shit work. Don’t send me shit or I will just send it back.” I started typing in an email to the developer who had sent it over. “I don’t mind taking a look and digging deep to find issues that aren’t apparent, but at least check your work before you send me something to review.” I said in the message.  


But before I sent it out I caught myself. This was my fault.  


We didn’t have a good process for debugging on this project, this was a good developer whom I had worked with a lot over the years. This was was clearly a process issue.  


Rather than hammering on a developer who was probably doing the best as he could, I decided to pull back and reset the process. The project was small, but it still needed a thorough QA process.  


Instead of sending out an angry email, this time I sent out an email to the PM on the project and asked her to implement a more complete QA process for the project and I opened up the resources she needed to get the work done.  


A week or two later, I received another email asking for a review. There were still issues, but they were hard to find and not what I would expect to see a developer catch. I was happy to go through and find every issue I could from that version of the system.  


ProTip: It’s easy to blame a developer for not checking their code, but at the end of the day it’s your fault if the proper processes aren’t in place to support your developers. They work at your bidding, so do what you need to do to make them successful.

### What to Expect From Developers

Different developers have different levels of skill, experience, accountability, etc. Great developers can be terrible time managers and vice versa. People are not equal in all areas, and getting the right people to do the right job is one of the most challenging aspects of any project.  


A book could be written on what to expect from developers, how they think and what they should and shouldn’t be responsible for, and many have. Rather than going into what to expect from developers, my recommendation is to start by [reading at least the first 3 chapters of “The Mythical Man Month” by Fred Brooks](https://www.amazon.com/Mythical-Man-Month-Software-Engineering-Anniversary/dp/0201835959). This will give you a great understand of who you are working with, how they think, and what you should expect from them.

### Managing Your SaaS Development Team

Project management is an entire profession, and we can’t cover that body of knowledge in this book. However, as noted previously multiple times, I highly recommend taking a course on Project Management with a focus on [Agile Development Methodology](https://www.atlassian.com/agile) if you are going to be a part of the management team or if you are an entrepreneur wanting to build a SaaS. If you go forward on this, you will have to learn it one way or another. Better to learn it up front than to waste money making mistakes.  


All that said, there are some things that you should know about SaaS development and development in general.

#### Developers are optimists

They just are. Even the ones who say they aren’t. So make it easy on yourself and your team. Whatever time they give you, at the very minimum, increase it by 20% in your head and on your projections at the very minimum. If you can, take whatever they gave you and double it in your projections. If you do this, you will almost always make your deadlines. Never go below a 20% increase in your projects, ever. Don’t tell them that you’re doing this, just do it and keep it to yourself, then smile when they make the deadline you thought they would make in the first place or beat your expectations.

#### Communication

So much is going to change in the build of your system. Hopefully, I have hammered into you by this point how important it is to plan as much up front as possible. But things are still going to change. There will be things you didn’t consider. The landscape will change, you may pivot, you will learn things you didn’t know previously, and the system will change. It always happens.  


So a key aspect of this entire process is making sure that everyone knows what’s going on as it changes.

Team meetings

I recommend doing meetings with your team at least three times per week, and potentially much more than that. For SaaS systems I am managing, I generally meet with each team lead DAILY. A study of [Agile Methodology](https://www.atlassian.com/agile) will help you streamline this tremendously.

#### Brooks’s Law

This is another area of the [Mythical Man Month](https://www.amazon.com/Mythical-Man-Month-Software-Engineering-Anniversary/dp/0201835959) by Brooks.  


What this says is that adding another developer to any substantially complicated project \(as SaaS systems often are\) halfway or later in the build of that project does not decrease the build time, it increases it. This is because the amount of time it takes to gain the ‘tribal knowledge’ gathered in the first portion of the build of a system is greater than the amount of time it takes to build the rest of the system.  


This applies more or less to different systems in different ways. Sometimes it doesn’t apply these days at all. But the important thing to remember is that very often, just throwing more people and money at something won’t make it go any faster, especially after a certain point. This is very similar to the [“Law of Diminishing Returns”](https://en.wikipedia.org/wiki/Diminishing_returns) you may recall from your Economics class in college or high school.  


Here is what the [Wikipedia](https://en.wikipedia.org/wiki/Brooks%27s_law) has to say about Brooks’s Law:  


“According to Brooks himself, the law is an "outrageous oversimplification", but it captures the general rule.  


Brooks points to the main factors that explain why it works this way:  
  


1. It takes some time for the people added to a project to become productive. Brooks calls this the "ramp up" time. Software projects are complex engineering endeavors, and new workers on the project must first become educated about the work that has preceded them; this education requires diverting resources already working on the project, temporarily diminishing their productivity while the new workers are not yet contributing meaningfully. Each new worker also needs to integrate with a team composed of several engineers who must educate the new worker in their area of expertise in the code base, day by day. In addition to reducing the contribution of experienced workers \(because of the need to train\), new workers may even make negative contributions, for example, if they introduce bugs that move the project further from completion.  
2. Communication overheads increase as the number of people increases. Due to combinatorial explosion, the number of different communication channels increases rapidly with the number of people.\[3\] Everyone working on the same task needs to keep in sync, so as more people are added they spend more time trying to find out what everyone else is doing.  
3. Limited divisibility of tasks. Adding more people to a highly divisible task, such as cleaning rooms in a hotel, decreases the overall task duration \(up to the point where additional workers get in each other's way\). Some tasks are less divisible; Brooks points out that while it takes one woman nine months to make one baby, "nine women can't make a baby in one month".”

Please keep this in mind as you build your SaaS as it applies in most cases.

#### Positivity is Key

Doing development work with good people and keeping them working is all about positivity. In development, you are dealing with tens, hundreds, hundreds of thousands, and very often literally millions of variables.  


People, especially entrepreneurs who want and need movement, see the mistakes. That one spelling error or broken image is all they can see, especially if they are in charge of the sales and marketing. But it is important to remember all the things that had to go right and all the work that had to get done to get to the point where you only see that ONE MISTAKE.  


Someone just missed one thing out of a million, so be careful how you address those issues. It is important to take into consideration what people did right as much as what was done wrong. When you see a mistake, think about all the other things that went right to get to that point, then think about the relative amount of work it will take to fix that one issue. Next think about the impact of an upset email vs. a positive one. It makes a big difference, so be careful with your words. Happy people work faster. If your team feels appreciated, they will work faster and harder.

#### Good; Cheap; Fast -- Choose Two.

This is a fundamental concept to understand. [One of my first videos was on this concept.](https://www.youtube.com/watch?v=ERRz7Ju5EpE) It is simple, but powerful. What this means is:  


If it’s good and cheap, it won’t be fast.

If something is good and you don’t spend much money on it it, the odds are whomever is building it, isn’t going to build it fast. That is because if you have someone who knows how to build something well, they are in demand from other organizations to build the same kinds of things. They are almost always going to prioritize the thing that is paying them more -- because they have to.  


This is especially true in SaaS development because these systems are large, complex, and time consuming to build, and anyone who is worth their salt is in demand to build these kinds of systems right now.

If it’s good and fast, it won’t be cheap.

For exactly the same reason as the previous item, if something is done well and done quickly, it is going to cost more. You have a set amount of time it will take to build the system. The only way to decrease the amount of time is to decrease the functionality of the system in one way or another. So if you build it well, it costs more time, and to fit more hours into less days requires more people or longer days. Both of these increase your cost.

If it’s fast and it’s cheap, it won’t be good.

Think you’re getting a deal? One company is offering you something for a lot less than the others, so why not right? Let’s break it down one more time. It will take a set amount of time, with some variance but not that much, for any company to build the system. One company is cheaper and faster, that means they are using less expensive people and more of them. There is a bottom in pricing in this industry, no matter where you go in the world. Development is a worldwide business, so people in countries that have a lower cost of living that really know what they’re doing still know what they can charge, and it isn’t $10/hr.  


So think about this, if there is a minimum rate for good developers, it will take a certain amount of time to do a project within a slim variance, and you have set number of features and thus time required. Then if someone is offering a cheaper price and to do something fast, they are either cutting time somewhere or don’t know what they’re doing. Unless they specifically show you that they have done the thing in the past, they almost certainly don’t know what they’re doing and you are going to have to start over.  


This applies to all types of teams

What people don’t think about when they think about this rule is that this applies no matter what kind of team you’re working on. A SaaS project ALWAYS takes a certain amount of time, no matter who does it. Often times, more experienced, and thus more expensive people are faster. But the project still takes a certain amount of hours. So, if you have a team you put together, an agency, or your good friend Bill Gates doing this for you, if they are cutting or you think they are cutting you a deal these principles STILL APPLY.  


So remember, if someone is going to ‘cut you a deal’ and you value time or quality of your product, know what you’re getting into. \(buyer beware\)!  


Caveat emptor \(buyer beware\)!

#### How to tell if your development team is working

This is a great question that so many entrepreneurs don’t know how to answer. With designers, you should be able to see the designs they are working on and see the changes they’ve made. But with developers, how do you know what’s going on?  


Here is the secret. Watch their commits in their code repository. Better yet, integrate them into your communications system, such as Slack. This way, you can see every time someone adds something to the code base.  


A commit is an addition of code to the system. It doesn’t get integrated into the testing or live server, just into the code repo. Bear in mind that the number of commits aren’t necessarily representative of the actual amount of work being done. But if you have good Code Repo Branch Management, your developers should be committing for every different ticket they are working on and you should be able to see the code commits flashing across your desktop. You don’t have to know how to code to take a look and see if commits are being made.  


What this looks like in the code repository:

![](https://lh4.googleusercontent.com/X6hjGV9qvgDULPmMZuvIGdOd4SUMTQOvEkNJWBXhIuHCkJrCP5rzKVI5JJmgBjTPnP4aq_9p-LD2Tcukxkv0rFVA-QJwjAmiXoOJ8B5gU5Ar-PElBg7ZGAQYSSCwB3Z1zRRdciop)

This is what  I see on Slack when things are being worked on:  


![](https://lh4.googleusercontent.com/oNoxU3lmKWP-UQUcg3xs6uqeeW8mmz-gj7VcbCGMvuWbYdoIq-h8Bq7gQRgXqwJZ2nc3opU1AdSMj3nIe4uqO9fwlQtfa5XOE-OGaxYPluErUAp-sdIqGh1wMLJJFmon5BpEXh9U)

If I know who is supposed to be working, when their deadlines are, and that they are doing development, I know that I should be seeing this kind of thing coming across my desk all the time. If I don’t see commits being made some particular day, I know that person is either not working or working on something really complicated where they are not making commits or taking a long time to make commits.

### Things you do and do not know in SaaS development

In most projects we have things we know and things we do not know. But there are also variations of these. Before going into your development phase, or any business for that matter, it is good to have an understanding of this concept.

#### Known knowns

We know that we know this. This is usually something that you or someone on your team has done before, and they understand this item thoroughly. Think of this one as knowledge.

#### Known unknowns

These are things that you know you need to figure out, technology you haven’t used before and know you’ll need to use or integrate, or general challenges you know you will need to uncover. Think of these as known risks or challenges.

#### Unknown knowns

This may sound a little redundant or silly, but it isn’t. A lot of times, unknown knowns are answers you or someone on your team knows or has an answer to, but hasn’t realized it yet. A good example of this would be that you need to build some library or some tool and someone on your team realizes that the tool that needs to be built is very similar to a tool they already built. Suddenly, they know how to produce this system very quickly, whereas otherwise it would have taken a long time. Think of this as untapped knowledge.

#### Unknown unknowns

This is the stuff that really messes you up. It is the risk you haven’t realized yet, or potentially never do. In SaaS development, a good example of an unknown unknown is a technical issue that the team did not foresee. These kinds of technical issues can be anything from a mild annoyance to disastrous to the project. The thing is, you don’t know, and you’re not going to know. However, the more planning you do up front and the more experienced your team, the less unknown unknowns you will get. Think of this as unknowable risk.

### Alpha Testing

Alpha testing is the phase where the thing kinda works, but not well enough to share with anyone other than people that know that it doesn’t work. In other words, if you’re at an alpha phase, that means you and anyone else looking at the SaaS knows that it doesn’t work or that some major features are pretty buggy.  


The alpha testing portion is technically part of acceptance testing. This phase is the first milestone in testing. What this means is that, in this phase, the team is going to generally test internally to see where the major problem areas are located.  


At this stage, the development team will review the system with you and will need to get it out to people to help test the system. If you have been doing a good job with your advisory board or community building, now is a great time to walk select members through the system to get feedback. Important note here, if you decide to share this with people outside of the company, they really do need to be selected people who understand there are going to be big issues in the system. For the most part, alpha testing will be done by internal developers and by you.  


#### Improvements at Alpha

You’re going to find all sorts of things you want to improve upon at this stage. But you need to remember what you’re doing and why you’re doing it at this point. Your goal is to GET TO MARKET, not build out every phase in the system.  


So take all those things you want to add, change, and generally improve, and put them into a bucket \(it’s called the Backlog\) to be done after you get to market. Your number one, most important, goal is to get validation that your system is going to sell, and you get this by getting people to pay you. If your system at its core functionality doesn’t sell then you have other problems to deal with, and adding things that are not core features now won’t help.

#### Content review at Alpha Testing

At the alpha testing phase, you should also be reviewing all the content on the system. This means every word, every rollover, every tooltip, everything. You’re going to have a lot of things that need to be done, and this is probably the easiest thing to do that is most often overlooked. If you add a step here to review everything, it will be a lot easier when you get to future phases if you have all the content taken care of here.  


#### Iteration and fixing issues

The way this book reads, it seems like you might get to this point, make some suggestions, then move on. It won’t go that way. By the time you get to the point where you’re doing this alpha test, you will know your product inside and out, and be steeped in development lingo. While this step has a fancy name and is a milestone, it’s just another iteration in the development process.

### Beta testing

This is the next major milestone to getting to launch. Sometimes, this step comes right on the heels of the alpha test phase. Other times it’s weeks, months, or even years after the alpha test. Once again, even though this milestone has a fancy name, it is just another iteration in the process.  


This step is important though because it represents your product being ready for testing by your users.  


Now it really is time to share your new contraption with the world! Since you’ve done an outstanding job of maintaining your relationship with the [advisory board](https://docs.google.com/document/d/1qLCH0YaNhxbutZeK9Oo87n9PhssDaHLkWLTPYW0UIMQ/edit#heading=h.amc9hmutfksq) and building a community, it’s time to put that relationship to use!  


In this step, choose a select few of these people and walk them through your product one at a time and get their feedback. Don’t just send it over to them and expect them to use it, actually meet with them in person or virtually and take them through the system. Get their feedback, understand their problems, listen to them, and most importantly make sure that they are going to pay for what you’re selling!  


The more people that test your system, the more bugs you will find and user issues you will overcome. When you get into beta testing, people are going to ask for new features, you’re going to want to add stuff, and you’re going to be tempted to build more things.  


#### Testing & Selling

My recommendation is to beta test and sell at the same time. Paying customers behave much differently than non-paying customers. They ask for different things and they see different things in the system. A paying customer is going to use a system to further their business, whereas a non-paying customer is not going to value the system as much, if at all. These are two completely different views on a product and you need the former, not the latter.  


Next, doing your testing is a great opportunity to sell your product. Users know where the product is in it’s development cycle, so if you give them a cut price for a set amount of time, or even forever, they are still paying while mentally buying into the value of the product.  


PROTIP: The SaaS build and launch process should be used as part of your marketing plan.

### Launching Your SaaS

The act of launching is as easy as making your marketing website connect the signup page to the credit card processing system so that when users try to sign up, they have to put their credit card into the system. Now, you can charge them when they have finished their trial or start using their value metric or whatever what it is that you determine how they are getting charged.  


That’s it. Technically speaking, you launched your SaaS. Anyone who wants to pay you for your SaaS services can do it now. There are of course a number of marketing related tasks that could and should be done, but from a development perspective, this SaaS is launched.  


As you probably figured out already, it’s a good thing you didn’t buy that ticket to Aruba to spend your millions just yet. You really just finished the very first step in the process. Now it’s time for the hard part, getting the thing out there.  


### Continuous Integration \(CI\) in SaaS

But wait, there’s more!  


I see you looking at the next chapter on growth. I see your eyes slithering down the page to that section that is calling out to you. But resist, friend!  


In the words of Yoda: “Luke! You must complete the training!”  


“But why?” you ask. “I want to read the chapter on growing the business!”  


Because remember all those things you wanted to change and improve in your SaaS? Remember how you didn’t like the way that feature worked, but you took my word for it and just went to market? Remember how long your backlog of features got to be before you got to this point? Remember those nice developers that you were paying to build this thing? They’re probably going to leave and get another job if they don’t have work to do here; and this is how you’re going to be doling out that work.  


Continuous Integration started as a part of what was termed [Extreme Programming \(XP\)](https://en.wikipedia.org/wiki/Extreme_programming). Developers love to sound impressive \(and if you’re a developer, you know I’m right\). Really, though, it was a pretty radical thought at the time.

#### What is Continuous Integration \(CI\)?

CI came about because lots of different people were working at the same time on large sets of code and they ran into what was termed “Integration Hell” when multiple people were working on multiple features at the same time using systems that did not allow for the same levels of integration as today’s systems, and basically they couldn’t get all the code to work together. It would take hours and hours or even days or weeks to get different groups’ features unravelled to the point where they could integrate these things together. So they created the concept of Continuous Integration, which basically means doing the integration continuously in smaller chunks instead of in gigantic blocks that will take forever to figure out how to fit together. Good idea, right?  


It started out as a process to make things fit together faster and stop wasting time, but as programmers do, they iterated on the idea over and over, and now we have this very impressive concept of CI with all sorts of steps to keep everything together.  
  


![](https://lh5.googleusercontent.com/RT5a3DRibCvvUwaU7Oy9QxQhptvhLTq7IUBk2EiqZbatJXAOUCXhcHe-KOEEdGiZvKzRs1BQucjvKQ_ad2O165I5NB6zfgHt7E6nzYpA4x91R5o9ehdWIJ6uwa6yNtyGmXPBbemf)

#### Why Does Continuous Integration Matter in SaaS?

It matters because now that you’ve got that first release ready to go, you also have about a million new things you want to add to it. Remember, continuous integrations started out as a [programming concept](https://en.wikipedia.org/wiki/Continuous_integration), but it grew into more than that. This should be interesting to you because it gives you a method and process for monitoring what your customers want, planning features, coding, building, and testing features, then releasing them, deploying them to your system, operating and monitoring/monetizing them, and continuing on the infinite journey of improvement.  


These areas are going to be very important steps to keep your SaaS from falling apart down the line, so don’t let this go in one ear and out the other!  


### Monitoring Your SaaS Environment

Now that your SaaS is up and running you’re going to need to look out for issues popping up -- and they will pop up. Implementing a networking monitoring tool will enable you and your development team to know when the site goes down, when the database fails, if you are overtaxing your environment, and in what ways.  


A couple monitoring systems I have used or team members have used include:  


* [New Relic](https://newrelic.com/)
* [App Optics](https://www.appoptics.com/)
* [Traceview](https://traceview.solarwinds.com/)

This will help you in two major ways, understand costs and being alerted to problems. If the site goes down or exceeds certain limits, you’ll get an automated alert and can check in with developers. As the system begins to grow, you’ll be able to see what aspects of the serving environment need to be upgraded. If you are on an environment like [Amazon Web Services \(AWS\)](https://aws.amazon.com/) or [Digital Ocean](https://www.digitalocean.com/), you or a developer will be able to log in and upgrade your server specs before users starts seeing degradation of operations or the systems fails altogether.  


My team normally uses Digital Ocean, and from here we setup our monitoring. Each one of the items below will send an email and a notice to our Slack dev channel notifying the team of issues.  


![](https://lh3.googleusercontent.com/EquL4MCk_AfmkOoQoPLv92e5H4kR911UowP2BgMNMg7uEbPV4hdaWl36z0OtQ6ilgUa_zfe0RlzyYCoYC1oyEgNpoBa0nOK5oPJG6799m19jQVBhpXP1m2njtuBzqmya6niCJSfG)

### What to expect in SaaS development

These are some lessons that I’ve learned from years of SaaS development that don’t apply to any one thing, but are good to know.  


1. If you’re working with a good team, expect for people to make their deadlines most of the time, but definitely not all the time.
2. Expect to be asked a lot of questions, a lot more than you expect.
3. That no one will understand the business side like you do. When you’re working with developers, most of the time you are working with people who are paid to do a job, not think about how the business will operate. So don’t expect them to.
4. If you are paying a full time team, they will actually get between 4 and 6 hours of good time in any given day. Or you will have workers that work in sprints for a week or two at a time then need a week off. But don’t expect your team to get a full eight hours per day of concentrated effort. Generally, developers just can’t concentrate for that long every day, day in and day out.
5. There will be things you didn’t plan on. Questions you didn’t realize were going to be questions, and problems you never thought would be problems.
6. Your timeline will be between twenty percent and three times as long as you initially planned, sometimes more.
7. If you are building your own team, you will almost definitely not get all the right people the first time. If you do, please let me know how you did this.
8. You will spend more money than you thought you were going to.
9. You are going to need more features than you initially planned to build. It is just the way it goes. No matter how experienced the build team or CEO of a system is, there are ALWAYS more features that get realized once the system gets underway than were initially planned.
10. Expect to learn things about your customers that you never expected. It doesn’t matter how you use the system or how you think people will use the system. They are going to find a way to use it in a way that you never expected.

