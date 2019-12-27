# Information Architecture Development

Once you have a validated idea and an estimate that makes business sense, it's time to dive into the deeper aspects of your system. Just like planning any complex machine, you will need to think through every aspect of use as you work out your information architecture. 

This chapter takes you, in-depth through what goes into building an information architecture. Even though it is just one of the first steps in building your SaaS business, it is the step that is so often glossed over, causing huge losses in time and money. The more you have considered exactly what will and will not go into your system at each phase, how each feature will work, and how you will optimize revenue at every step, then you will know what it takes to be successful in your SaaS business. 

{% hint style="warning" %}
I cannot stress the important of being as thorough as possible in the Information Architecture portion of your project. 
{% endhint %}

## What is an information architecture and why is it important?

An information architecture is a written description of your system. It describes every section, every page, every feature, how people use the system and very often why. It outlines the goals of each system and subsystem and describes them in a way that both a lay-person and a developer can understand. More importantly, the description of the architecture is granular extensive so that a designer or developer working on the system can understand what it is that is to be created. 

### A work in process

An information architecture is a work it progress, it is rarely ever 'done'. Every change to the system, every modification that someone makes should be described as best as possible within this document. As the system progresses, it's a smart idea to add the new features and new systems into this document and keep an up to date description of what you're doing an why. 

### Enterprise Agile vs. Agile or XP Methods

Some people may say that this is a 'waterfall' method and that it goes against the grain of contemporary Agile or XP methods. To some extent this is true, but when developing a new system from scratch. Having this document well thought out from the beginning will save you countless hours of work and time. If your team is working on an existing system and adding to it, then perhaps there are other methods as well that would be just as good if not better. But if you're going from the ground up, this is the blueprint for your house. It is the survey, the plans, the electrical and plumbing, and it's where your concrete is being poured. 

{% hint style="success" %}
The information architecture is the central document of your planning methods and the linchpin of a fast and affordable product launch. It is what enables you and your team to understand what you're building, cost your system ahead of time, and visualize what you're building before it is built. 
{% endhint %}

### Costing, Build, & Getting To Market

When building a SaaS, or any application, times and thus costs and deadlines can swing wildly with seemingly small changes to features. Knowing what you're building, how much time it will take, what changes impact different areas, and granularly breaking down cost and time estimates on your system are key to creating an a workable budget, building systems that can be rendered usable in a timely fashion, and therefore getting to market with enough budget left to market a working system. 

The lack of understanding about the cost and time it will take to build a system from start to beta is one of the primary factors that keep many, many digital entrepreneurs from getting to market with their tools. Having a well defined and well thought-out information architecture prior to beginning development on a system is critical to all of these things. 

## Parts of an information architecture

Withing a SaaS platform, the information architecture generally consists of the following major areas:

* System goals, user types, & user flows
* Project-wide tasks & notes
* Public-facing views
* User type specific views and notes
* Admin panel

Each of these items are described below:

### System goals, user types, & user flows

Before you begin any journey, you need to know where you're going. System explanations lack clarity without an understanding of what the system solves for users, whether the system if solving a knowledge gap, time gap, or both, how different user types are defined and what aspects of the system they do and do not have access to, and what the major flow of a user is within the system. 

#### System Goals

System goals are not monetary goals, but usage goals. The system goals are descriptions of how the system helps users solve a problem. Preferably, this section states in-depth the step-by-step flow of a user from start to finish. Sometimes just writing out these goals help an entrepreneur or product manager realize things about their system that were hidden previously. In addition to the broad steps a user will take and what the system does, the system goals area may also include competitor benchmarks, product usage goals, and non-functional requirements like speed or load times. 

#### User Types

Without an understanding of who will use the system and what is important to their role, system features or requirements may not make sense. It may also be unclear as to the best ways to price systems or restrict access to certain features for certain user types if user goals are not understood. So a clear explanation of each user type, the user type's job role and reason for using the system, their permissions to different areas in the system, why they have been assigned those permissions, and the flow of each user through the system is necessary for your team to conceive system features and for team members to develop the system.

{% hint style="info" %}
If you can't explain it, how do you expect someone to build it?
{% endhint %}

#### User flows

Very often, different user types have very different areas of your system they use or use them in very different areas. For example in a CRM system, a Sales Manager may be much more interested in the performance reports for their team than actually inputting anything into a CRM system, but may also need to delve deep into the call logs or emails for different sales people to assist them in increasing their conversion rates. The sales person is going to be entering data about the people they called and getting back reminders on who to call and what they talked about last. Finally, the CEO is primarily interested in the success of the group as a whole and forecasts on incoming sales which may simply be delivered to his enterprise business intelligence system via an API call. 

All of these different user types are interested in different aspects of the system and may have different access to the different areas. Understanding how each user type uses the system and flows through it to meet their goals is an important first step for anyone reading the document, so it should ideally be at or near the top of the page. 

### Project-Wide Tasks & Notes

Now that you have identified who uses your system, what their primary goals are, and how each user type uses the system, we start working on the architecture portion of the system. There are several top-level tasks that apply to all areas of the system or that must be done prior to starting work on features or pages. Later in this chapter we will dive into exactly what these top-level tasks include. 

## Chapter Outline

1. What is an information architecture and why is it important in a SaaS?
2. Parts of a SaaS architecture
3. How to write an information architecture for a SaaS
   1. Considerations
      1. Features, pages, & views
      2. Project size
      3. Team
      4. Security
      5. What is and is not necessary
      6. Order of areas
      7. Waterfall plan, Agile build
      8. Granularity & Meticulosity 
   2. Description & Structure
      1. Designer, developer, and stakeholder should understand what is to be built
   3. Notes
   4. Tags
   5. Costs and assignments
   6. Document reviews
      1. All team leads
      2. Stakeholders
      3. The document review meeting
   7. Finalizing your document for MVP

## User Areas

1. Project-Wide tasks and notes
   1. Planning
   2. Team setup
   3. Kickoff
   4. Systems Setup
   5. Project management
   6. QA
   7. Launch
2. Creative
   1. Determining Style
      1. Mood boards
      2. Creative Brief
      3. Flows & Wireframes
      4. Style Guide - examples
      5. Mockups
3. User Areas & Systems
   1. Header & Footer
   2. Onboarding
      1. Choosing a plan
      2. Credit card info
      3. User and/or company account setup
      4. Email Verification
      5. User education
         1. "Requiring" watching a video
      6. Onboarding emails
      7. Onboarding revisions
   3. Authentication
      1. Log in and Log out
      2. Secure passwords
      3. Forgot your password
      4. Two-Factor Authentication \(TFA\)
   4. Dashboard
      1. Considerations
   5. Account Management
      1. Permissions management
         1. Standard features
            1. Account owner
            2. Account manager
            3. Team member
            4. Other user types
            5. Teams
            6. Editing plans
            7. Change passwords
            8. Change username - note on emails not being id's
   6. Transactional Emails
      1. Setup
         1. Standard Design & Build
      2. Account Creation
         1. Account created
         2. Email Verification
      3. Payments / Billing
         1. Initial payment upcoming x2
         2. Receipt of payment made / thank you
         3. Receipt of payment made for app addition / upsell / thank you
         4. Credit card expiring
         5. Credit card expired
         6. Credit card payment failed
         7. Access removed due to expired card
         8. Refund made
         9. Renewal
      4. Notifications
         1. Invitation for new users
         2. Message received
         3. New account created or installed
         4. Likes or shares
         5. Notification of use
         6. Task completed
      5. Alerts
         1. Password reset
         2. Privacy Policy Update
         3. Account Safety Alert
         4. Membership or benefits update
         5. Event Reminder
      6. Subscriptions
         1. Free trial ending
         2. Plan cancellation
   7. Notifications
      1. In-system notification system
   8. Subscriptions
      1. Taking money \(billing\)
      2. Invoices
      3. Team billing
      4. Pricing
      5. Value metric
      6. Discount codes
   9. Localization
   10. Chatbot Setup
   11. Analytics Setup
   12. Affiliate Sales
   13. Support Requests
   14. System Specific features

## Admin Panel 

1. Authentication
   1. Protecting your system
2. Dashboard
3. Add / Remove users
4. Add / Remove Teams
5. Change user roles
6. Edit plans and pricing
7. User impersonation
8. General system statistics

## Marketing Website











