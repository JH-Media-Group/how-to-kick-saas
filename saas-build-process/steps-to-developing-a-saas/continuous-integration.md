# Continuous Integration

## Change is a part of life

The [concept of continuous integration](https://en.wikipedia.org/wiki/Continuous_integration) in SaaS includes the precept that your system is always changing and is the process of dealing with this continuous change. 

This is an iterative, looping process of:

1. Release
2. Operate
3. Measure
4. Plan
5. Code
6. Build
7. Test
8. Release \(back to top\)

Beyond the simple concept that continuous integrations happens in SaaS, there are also tools that enable the flow of this process. Fortunately, a lot of these tools were built for developers, by developers and are open sourced and free to use for your project. 

These systems integrate other tools described in this document such as:

* [Code repository](../tools/code-repositories-in-saas-development.md#what-is-a-code-repo)
* Unit and regression testing systems
* [Development environments](../tools/development-environment-and-dependencies.md#development-environment-and-scaling)
* [Project management tools](../tools/project-management-tools-in-saas-development.md)
* Documentation systems

When a release candidate is ready for release and the lead developer pushes the button, an [automations server such as Jenkins](https://jenkins.io/) \(also an open source/free system\) automatically pulls the right code, runs unit and regression tests, deploys to the development environments, updates documentation, and makes entries into the project management system. The automation of this process can save you countless hours of time. 

## Continuous Integration \(CI\) in SaaS

But wait, there’s more!

I see you looking at the next section on marketing. I see your eyes slithering down the page to that section that is calling out to you. But resist, friend!

In the words of Yoda: “Luke! You must complete the training!”

“But why?” you ask. “I want to read the chapter on growing the business!”

Because remember all those things you wanted to change and improve in your SaaS? Remember how you didn’t like the way that feature worked, but you took my word for it and just went to market? Remember how long your backlog of features got to be before you got to this point? Remember those nice developers that you were paying to build this thing? They’re probably going to leave and get another job if they don’t have work to do here; and this is how you’re going to be doling out that work.

**Continuous Integration** started as a part of what was termed [Extreme Programming \(XP\)](https://en.wikipedia.org/wiki/Extreme_programming). Developers love to sound impressive \(and if you’re a developer, you know I’m right\). Really, though, it was a pretty radical thought at the time.

## What is Continuous Integration \(CI\)?

CI came about because lots of different people were working at the same time on large sets of code and they ran into what was termed “Integration Hell” when multiple people were working on multiple features at the same time using systems that did not allow for the same levels of integration as today’s systems, and basically they couldn’t get all the code to work together. It would take hours and hours or even days or weeks to get different groups’ features unravelled to the point where they could integrate these things together. So they created the concept of Continuous Integration, which basically means doing the integration continuously in smaller chunks instead of in gigantic blocks that will take forever to figure out how to fit together. Good idea, right?

It started out as a process to make things fit together faster and stop wasting time, but as programmers do, they iterated on the idea over and over, and now we have this very impressive concept of CI with all sorts of steps to keep everything together.  
  


![](https://lh5.googleusercontent.com/RT5a3DRibCvvUwaU7Oy9QxQhptvhLTq7IUBk2EiqZbatJXAOUCXhcHe-KOEEdGiZvKzRs1BQucjvKQ_ad2O165I5NB6zfgHt7E6nzYpA4x91R5o9ehdWIJ6uwa6yNtyGmXPBbemf)

## Why Does Continuous Integration Matter in SaaS?

It matters because now that you’ve got that first release ready to go, you also have about a million new things you want to add to it. Remember, continuous integrations started out as a [programming concept](https://en.wikipedia.org/wiki/Continuous_integration), but it grew into more than that. This should be interesting to you because it gives you a method and process for monitoring what your customers want, planning features, coding, building, and testing features, then releasing them, deploying them to your system, operating and monitoring/monetizing them, and continuing on the infinite journey of improvement.

These areas are going to be very important steps to keep your SaaS from falling apart down the line, so don’t let this go in one ear and out the other!

