# SaaS Build Lessons

Congratulations! You were able to successfully pre-sell your new SaaS idea and you’ve got validation that this business is going to work. I’m so proud of you! Now, we need to build the thing. This part gets a little technical, but since you’re a SaaS business owner now, that’s fine because you know you’re going to have to understand this stuff to make the business work, right?

## Build Process Lessons:

I’ve made a lot of mistakes since 2007 when I started my first SaaS. These are the most important lessons I wish someone had told me about or made me do starting back then.  

Check out the webinar:

{% embed url="https://www.youtube.com/watch?v=dSRg1oIy6eg" %}



## 1. No one is going to guide this better than you.

You need to understand what is happening, what the process should be, what is going on, when to listen to people, when to not listen to people, and how to guide the build of the system. You cannot expect anyone to guide this process better than you.

## 2. This is a construction project. 

Just like building a house, office building, high rise, or factory, this project has very similar major steps and labor costs but not the materials costs, except perhaps software costs. You need to understand the process to be able to guide it. 

## 3. The more you plan up front, the less your team will work and the less the project will cost.

It sounds right, but when you get into it, it starts to not feel right when you’re spending thousands and thousands of dollars on a plan and can’t see any revenue being produced. This comes back to the construction project analogy above. When you build a house, you don’t just worry about how many bedrooms and bathrooms you’ve got. You have to think about the color of the door knobs, the paint on every wall, the color of the bricks, the type of cement being used, what kind of carpet you’re adding, and a thousand more things. 

Every time you don’t consider those things, the builder is going to have to stop and ask you what you want. Every time they have to stop it costs you money. There will be people that you’re paying just waiting around to do things. You will have to take time out of your schedule, and it will generally just take longer to do. 

For one or two items, it is no problem, but these issues compound on top of one another. Because you changed the position of the toilet, now the electrician has to come back in and move the wires for the switches on the wall, the plumber has to drill another hole in the foundation, the framers have to come back in and move a wall, and your price didn’t go up by the cost of moving a toilet, it went up exponentially, as did the duration of the project.This is the exact same thing that happens in SaaS build and why **scope creep** can become so devastating. 

So, spend the money up front and know what you are going to build. Your cost savings will be huge.  

## 4. SaaS systems live and die on User Experience \(UX\)

If a system is not easy to use, people won’t use it. A little frustration a couple of times will drive users away from the system, and the likelihood of them returning is not good. The best way to avoid this, is to pay a UX designer who has done this before. That doesn’t mean that they need to know your industry in and out, it just means they need to have been doing UX design for a while and have had the time to make the mistakes on other projects so they get yours right.

## 5. Choosing the right technology can make the SaaS build process more or less expensive and successful.

There is so much to be said on what systems to use, and they change regularly. What’s important here is that you choose a system that is community-supported, has a lot of people building on that system, and is built on a platform that isn’t going to go away anytime soon. What’s right for your project in many ways depends on the project as well as on the team that is building it. If you choose the right team, then they will help you choose the right platform.

## 6. Adding new features during the build of the MVP can crush your business. 

This is called scope creep, and it can kill your business before it ever starts. There are a lot of reasons that adding more features in the middle of a SaaS project are a bad idea, but the main one is that it keeps you from truly testing and validating your idea and bringing in revenue. People tell you what they want with their money, not their words. So if you have a system that is taking forever to get to market, it means you are spending money on something that may or may not cash flow.  

Also, if you have revenue coming in, you can fund your operations. If not, it’s coming out of your  capital outlay, which is limited.

## 7. As soon as you have project validation, start building in unit tests.

If you are just validating your MVP, I would say don’t worry about building tests to right away. However, if you are 95% or more sure that the system is going to fly, and you already have buyers waiting, then you should consider building tests to start. 

A unit test is a tool process that confirms if a system is working or not. It generally gives a pass or fail response to a very specific set of variables. For example, if you try to log in and enter the correct username and password, you should be taken to the dashboard of your system. If the system tries to log in and isn’t being taken there, then the test failed. 

Tests can be broad or very specific, but they always measure one thing, one step, or one process per test. A specific example is in our BrainLeaf system where if a user enters a number of hours for a task, the task items should update, the total number of hours should update, the top level task should update, and the total price should update. This should also be reflected in our payments to contractors, milestones for receivables to clients, in our reporting areas, in the client listing where it shows total spend per client, and on the main projects listing. To write this one test, to show that updating a single change in a single form works takes days to implement. 

But on the flip side, and this is important, if you have to manually test every variation of changes to a system, the change in testing time grows quadratically or exponentially, depending on the system. The testing time alone, if done manually, can and will very quickly become more time intensive than the actual building of the system. 

### Regression Testing

Next, these unit tests also include regression testing. This means that as you build a new feature in the system, old features are going to break. An automated regression test will show you which current features broke, and how, when you implemented the new system.

Tests generally take between 10% & 20% of the total build time to construct and implement -- however, the larger the system is, the more time the tests save. Furthermore, tests take longer to build after features have been completed than during the build, so adding them later is going to add time that you may not have until you have to implement them. 

{% hint style="info" %}
**PROTIP:** Don’t skimp on your regression tests or you will regret it! 
{% endhint %}

### SaaS System Build & Continuous Integration

No SaaS system is ‘done’. They are always changing, upgrading, pivoting, entering new markets, etc. When you first build a system, you need to get that MVP out the door and into your users’ hands as quickly as possible. This first step is referred to here as the ‘SaaS System Build.’ 

After the system is built, you are going to enter an ongoing phase called “continuous integration”. This is the process of continually adding to your SaaS platform. This step is going to start as soon as your MVP is done, and potentially before then. As long as you have a successful SaaS, you are going to be in a continuous integration phase where you are always adding to the system. Take this into account in your operations costing!

Aspects of continuous integration are discussed throughout this document.

