# Parts of a SaaS

Before getting into how you’re going to plan, price, build, sell, and grow your SaaS business, let’s get acquainted with the major areas of a SaaS. The areas examined below are aspects of most SaaS systems, although not all of them.

## Public facing sales & marketing website

This is one of your primary sales and marketing tools. This tool can be very large or fairly simple, and it must explain to your target market:

* The value of the system
* What the system does for this group
* How the system works with the target group’s existing processes
* How to get started, which leads to pricing and onboarding
* Any necessary support systems
* Pricing
* If content marketing is necessary, a blog
* A knowledge-base or support area where users can learn to use different features within the system.

These needs are generally met with an architecture consisting of the following pages:

1. **Home** - Shows value of system to target market.
2. **Features or Tour** - Explains how the system works and explains in detail how the tool accomplishes the goals of your target market.
3. **Pricing** - Clearly defines the price of the system and the different options for purchase.
4. **Blog** - At the time of writing, this is used primarily for content marketing, but also very useful for community management, customer education, email marketing, and public relations.
5. **Knowledge base** - Usually a system with a separate management system that is used to educate users on how to use aspects of your SaaS system.

There are a lot of other pages that are often added to a SaaS system marketing website, but these are the items that most need to at least get started. [A full explanation of the public facing website is listed in the chapter on Acquisition](../acquisition-gaining-saas-users/the-marketing-website.md).

## Account management system

The user management system, in this case, is referring to a system that enables the user to manage themselves and their account. The user management system includes aspects such as:

* Log in / log out
* Account creation
* Account deletion and/or suspension
* Edit user information such as name, email, phone number, etc.
* Subscription type management
* Team management to invite other team members to the SaaS
* Permissions management to grant access to different features of the system to different team members

## User Onboarding

When new users sign up for the system, the onboarding system takes them through basic setup and educates the user on how the system works, instills certainty that the system meets their needs, and gathers information from the user that is necessary for use of the system.

The onboarding process is a key portion of both acquisition and retention. It integrates into your marketing and sales processes and is integral to the success of your system.

User onboarding systems vary drastically depending on what the system does. Take a look in the chapter on traction for more information on user [onboarding systems and tricks](../activiation/activation/onboarding.md) to improve this process with education, simplicity, UX, and processes.

## Payments management system

Payments management refers to a place where transactions, subscriptions, plans & editions, refunds, and other payment-related features can be viewed and processed. At the time of writing, commonly used systems were [BrainTree Payments](https://www.braintreepayments.com/), [Authorize.net](http://authorize.net/) and [Stripe](http://stripe.com/). However, most payment processors can be used for this purpose. Tools such as the ones noted above have great APIs for SaaS payment processing, but there are a large number of other payment processors that work just as well and are substantially less expensive.

An important note about Stripe, BrainTree Payments, and other similar systems are that initially it is advantageous to start out using these systems because the initial cost of implementation is low, but after you hit a certain credit-card based revenue point, the cost of developing a custom system becomes lower than continuing to use these systems. That being said, my recommendation is to start out with product validation and the fastest, easiest system to build before adding any additional features. 

## User Payment Management Area

This refers to the system used by users to manage their payments. This can be as simple as a list of invoices and as complicated as a system for increasing seats in the system, editions, and more. 

The user payments area needs to include, but is by no means limited to, transactional emails that inform a user that they:

* Have paid a bill \(a receipt of payment\)
* Owe money - credit card expired, payment did not go through, etc.
* Owe more or less money than previously. This could happen if the users edition was changed, team members were added or removed, more credits were purchased, etc.

## Portal/Dashboard

The portal or dashboard system generally refers to the main page the user sees after logging in and the interface on that page. When a user logs in, this is the area that they see where they can interact with the system, view system statistics, navigate to user and team management, and generally use your fancy SaaS system.

When building your SaaS portal/dashboard system, I highly recommend using an extensible, pre-built framework for this such as Angular Material, Bootstrap, Foundation by Zurb, or one of the many systems utilizing a pre-built framework. Especially if you are building an MVP, having a system that can be modified quickly and easily is critical.

## Admin panel

The administration panel is the top item in my opinion that is not considered or not fully considered by new entrepreneurs when planning out their SaaS. The admin panel is a system that enables the administrators of the system to manage data within the system. 

Some common features of the admin panel in a SaaS system include:

* User management
  * Adding new users manually
  * Editing user information
  * Deleting users
  * Banning users
  * Logging in as a user so admins can see what they are seeing and edit their accounts through the system graphical user interface \(GUI\)
* Promo codes
  * Adding, editing and deleting
  * Managing users with promo codes
* System maintenance mode
  * Sometimes you have to take the system down for maintenance, and you need a place to do that from.
* Communication with users
  * Send system-wide or individual notifications to users
* Viewing system use statistics
* Data entry and management
  * This can be especially important if the SaaS is data-based, meaning that what it is selling is data.
  * If your system fills a knowledge gap, than this area is especially important. 

{% hint style="info" %}
**PROTIP**: The easier it is for your team to enter and manage data the faster you’ll be able to grow your company.
{% endhint %}

## SaaS Transactional Email Management

When you sign up for a SaaS and it sends you one of the following automated emails:

* Welcome to the system
* Verify your email
* You made a payment
* Someone was added to your team
* Your account was cancelled

See the full list of transactional emails in the [SaaS Build Estimate Spreadsheet](https://drive.google.com/open?id=1qC2h5e_YFvCAAoWA4Vaj1U7k7XPjsUMuqVoLKLAZh0I)

This is what is known as a ‘Transactional Email’. A transactional email is an email that is automatically sent by the system because someone in or using the system did something that triggered it. Generally, this is what is known as a ‘transaction’, and thus a ‘transactional email’. Coincidentally, these events are often triggered by monetary transactions, but they are not specific to just that kind of email.

## User Tagging, Triggers, & Lead Scoring

This is probably the second most forgotten aspect of SaaS systems when an MVP is being developed. When a user signs up, you’re going to want to add them to your marketing email list, then when they take certain actions within the system, you’ll want to add them to different lists, automatically send them different kinds of information, and score them or mark them for upsells. If you implement a Chatbot, you’ll also want to know what your user is doing to best answer their needs in the most efficient way possible.

For each of these actions, you’ll need a way to track the users within the system, know what they did and did not do that you wanted them to do, and generally how they used the system. This is something that is a lot easier to build in from the beginning than to add later. Besides, as soon as you launch your system, you’re going to want this data, so plan on building in at least a minimal system up front!

[For more on this, take a look at the chapter on marketing automation.](../acquisition-gaining-saas-users/marketing-automation-in-saas/)

## Third-Party Management, Tracking, & Reporting Tools Integration

As soon as you launch, you’re going to want to look at how people are using your system and interact with them outside of just emails. You’re going to need to know things like:

* How am I doing money-wise? \(profitwell.com, kissmetrics.com, baremetrics.com\)
* Am I meeting my financial goals? \(same as above\)
* Are people having trouble and leaving without me knowing? \(luckyorange.com, hotjar.com\)
* How are people finding me? What are they searching for? What is my conversion rate? \(analytics.google.com\)
* Why is or isn’t my system selling? Are users in the system confused about the use of certain items? \(luckyorange.com, hotjar.com\)
* Are my sales people effectively tracking users in the system and selling to them? There must be a thousand different CRM systems out there for this. Some of the ones I have used are:
  * [Pipedrive](https://www.pipedrive.com/) \(what we use right now\)
  * [ZohoCRM](https://www.zoho.com/crm/)
  * [SugarCRM](https://www.sugarcrm.com/)
* What are people saying about my system outside of the actual system on social media? What can I do to rank my system higher on the search engines? \(SEMrush.com, ahrefs.com, moz.com\)
* Are people getting my emails? \(mandrill.com, mailgun.com\)
* If people are having trouble with different areas, how can I help them? Am I doing enough to help them? \(intercom.com, chatbot.com, convertfox.com, verloop.com\)
* How can I get people to upgrade to the next edition or level?
* What can I do to help people that are on my sales website buy a subscription? \(intercom.com, convertfox.com, verloop.com\)
* And loads more…

For all the questions listed above, there are SaaS systems to answer those questions, and you’re going to want and need to use those systems. Plan on integrating these systems up front, rather than later because as soon as you launch you’re going to need them. The systems noted are just the ones I have experience with, so make sure to do some research before going forward with any of these and make sure the solution fits your needs.

## API - Application Programming Interface

The API enables developers to work directly and securely with aspects of your system. If you want to enable other systems to get information into or out of your system, then you're going to need an API and documentation. With the exception of systems that are built specifically for developers or have some aspect that requires them to be connected to other systems, like an add-on or plugin into another system, then most systems start with just their core functionality and develop the API after phase 1. 

But if the success of your application depends on being connected to other systems, then you're going to need to develop the API in the first phase of development. 

## Unit & Regression Testing

One of my top SaaS build lessons is on [unit and regression tests. ](../saas-build-process/saas-build-process.md#7-as-soon-as-you-have-project-validation-start-building-in-unit-tests)

Regression testing is a way of building automated tests that tell you if the system is working correctly when you deploy new features. Depending on the type of SaaS you are building and how well validated the system is at launch, you may or may not want to start off building tests into the initial system.

There are a large variety of testing suites. [My favorite system for testing SaaS systems at the moment is Katalon.](https://www.katalon.com/) It is free to use and a powerful system.

## Documentation

In a SaaS product development process, you’re going to be doing a lot. It’s a complicated web of interweaving ideas, systems, people, and money. So WRITE DOWN WHAT YOU’RE DOING. Please, for your own good, write down as much as you possibly can and share it with everyone, because you’re going to need it, and you’re going to wish you had if you don’t.

My recommendation for this is to [use Confluence](https://www.atlassian.com/software/confluence) for your documentation. It’s an Atlassian tool that integrates with JIRA, my top pick for development project management.

## Knowledge base

All those users you’re going to have are going to have questions, and lots of them. When there is a question for one customer it just takes a minute, but when you have a thousand customers, it scales at a one to one ratio, and you end up with it taking a thousand minutes. So a knowledge base where users can find answers or you can direct them for answers very, very quickly becomes a critical system. 

Some systems you may want to consider for your knowledge base:

### Wordpress with a knowledge base theme.

This is a lower-end solution, but it works. You can get started quickly and deploy a system that works well enough within a few hours. We’ve used the [HelpGuru theme](https://themeforest.net/item/helpguru-a-selfservice-knowledge-base-wordpress-theme/8465592?s_rank=4) a number of times and it is a good place to start.

### 3rd party SaaS knowledge base systems

There are a ton of 3rd party knowledge base systems out there. Some that we have used include:

* [Zendesk](https://www.zendesk.com/)
* [Confluence](https://www.atlassian.com/software/confluence)
* [Helpscout](https://www.helpscout.com/)
* [Intercom ](https://intercom.com)\(their knowledge base works hand in hand with their chatbot\)

### List of Knowledge base systems

[Quora has a great list of systems here.](https://www.quora.com/What-is-the-best-knowledge-base-software) Take a look for a full list.

## Customer Support Systems

Customers are going to have questions, they're going to have problems, and they're going to want to talk to someone about all of this. You could just put your email out there and have people email back and forth with you, but that's going to get real messy real fast when you have hundreds of customers with thousands of questions and several customer support team members trying to answer those questions. 

So rather than killing yourself and your reputation, how about starting off with a system that is going to help you manage tickets and requests right away? 

My recommendations for getting started are:

* Helpscout
* Zendesk

These systems all allow you to scale up and add more and more team members to a support infrastructure that will scale with your business. 



