# Continuous Integration

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

* Code repository 
* Unit and regression testing systems 
* Development environments 
* Project management tools 
* Documentation systems 

When a release candidate is ready for release and the lead developer pushes the button, an [automations server such as Jenkins](https://jenkins.io/) \(also an open source/free system\) automatically pulls the right code, runs unit and regression tests, deploys to the development environments, updates documentation, and makes entries into the project management system. The automation of this process can save you countless hours of time. 

