# Lead Scoring, Tagging, & Triggers

I highly recommend reading [this Medium article by Myk Pono on Lead Scoring](https://medium.com/@myxys/how-to-design-lead-nurturing-lead-scoring-and-drip-email-campaigns-9961024f6605) as well as a great book on this, [The Definitive Guide to Lead Scoring by Marketo](https://www.marketo.com/definitive-guides/lead-scoring/). These texts will give you a deep dive into this area. In this chapter, I will try to distill both of those into a more simplified set of principles and actions for you.  


![](https://lh5.googleusercontent.com/Dyd8RHamdkLdOk5MOGo35wQZdxbadOa_enwc0QpWrg4C45VMbjtl0L_8j-Ulz-s7yFDS2q4Al7CGOL8C7oXuY1HkyJIcdDekwUfUK5HRnAUxsFNU0rgsVFiMCldf3LM15aKnmyHo)

### What is Lead Scoring?

Lead scoring helps you identify who you need to be talking to and what information they need to receive in an automated fashion.

Lead scoring doesn’t specifically relate to emails, but in a lot of SaaS businesses, automated emails are a big part of the system. In many SaaS businesses, you have the following customer contact campaigns that should be in place.

## SaaS Customer Contact Campaigns

First the email campaigns. They are the easiest to create:

* Welcome campaign
* Onboarding campaign
* Nurture campaign
* Product engagement campaign
* Upsell campaign
* Renewal campaigns

In addition to email campaigns though, you also have things like:

* Chatbot messages for different user types, flows, etc.
* Different kinds of phone calls to be made to users
* Direct mail
* Actually visiting your customers \(this really happens\)

Lead scoring is going to help you figure out who needs to get which campaign and when in an automated fashion.

Before we can know what to send, we need to understand a few main indicators as well as the flow of the user lifecycle for a SaaS, then break them apart and put numbers to them:

* What part of the buying process your user is in \(described in previous section\).
* If the problem they have is what your SaaS solves
* If their actions show them to be a valuable lead
* Who they are or their customer persona, if that can be determined.

Flow:

1. Visitor - someone that visited your website
2. Prospect  - a user that downloaded a lead magnet
3. Activated User - a user that signed up for your system
4. Customer - a user that has paid for your system
5. Active Customer - a customer that paid for your system and is using your system
6. Loyal Customer -  a customer who paid for your system and is increasing their use of the system.

## SaaS Email Campaigns

Rather than building a complex formula, I like to think about this system in action or task focused process. In creating this system, we want to answer the question “at what point do I need to send what to who?” So let’s assign values and correlate those values to actions.

How sure am I that I am talking to the right person for my product? First we need to know who they are. So let’s assign some simple values to what we know about them. Different SaaS businesses are different, but here is how we monitor people at BrainLeaf. These methods were built up over time and review of analytics.

### Visitor gets:

* Educational information about their problem
* Asked to sign up for the system or for more information so we can better qualify them.

### Prospect gets:

* Product information
* Case studies
* Demos of the system
* Sales presentation

### Activated User gets:

* User onboarding
* Tips and best practices
* Offers for help
* Regular Newsletter
* Product updates
* Educational content
* Requests to become a paying customer
* Unfinished flows

### Customer gets:

* All items from activated user except for requests to become a paying customer
* Customer onboarding

### Active Customer gets:

* All items from activated user except for requests to become a paying customer
* Upsell campaign
* Notify user of usage limits
* Feature benefits
* New Releases
* Promotions
* Renewal campaign

### Loyal Customer gets:

* All items from activated user except for requests to become a paying customer
* Partnership campaign
* Personal relationship/word of mouth building campaigns

In addition to email campaigns there are a lot of other ways to reach out to your potential customers. These can be methods such as:

* Chatbot messages when the user views your marketing site or accesses your SaaS
* Social media messages or posts
* Direct mail
* An actual phone call
* A follow-up phone call.

{% hint style="info" %}
**PROTIP:** When you’re first planning your SaaS business, make sure to plan plenty of time to work on all of these emails. For each email, you’re going to need design, copywriting, and some amount of development. It always takes longer than you expect to do these. Also, don’t think that you’re going to be done after you finish up the first version of these, you’re absolutely going to iterate on these as soon as they start going out.
{% endhint %}

When it comes down to it, for the most part the emails that users are going to get fall into the lists of items noted above. There may be some variation, but it usually goes this way. However, how do you know where to escalate the user to the point where your sales team takes over?

## Lead Scoring

Lead scoring is based on two main things. The first is how much does the system solve their problems and how much does the user fit the profile to which you’re selling.

### Scoring Attributes

The more we know about the user, the more we can determine where they fall in our list. The first things we can almost always get is their profile information. This includes the following fields:

* Name
* Email
* Role
* Company Size
* Business Type

For each of these items we can assign a score, the higher the better. In the points example below, the name and email are not taken into consideration in points, but we have to have these to process the user, so we require them. Depending on what your SaaS business does, you will need more or less information, but this is a good start.

Next, we need to know if what the user is actually interested in what your system does or if they are just passing through. These kinds of actions are totally dependent on the system you’re building.

Depending on your drip email and marketing automation system, you may have either simple or customizable lead scoring systems. If you can customize your lead scoring, my recommendation is to escalate to your sales teams based on a score you set up in the system.

Below are some examples of how we initially set up our points system for BrainLeaf. It has since been changed, but it’s a good place to explore.

### Example Points System

Remember, we are not looking for Freelancers. Our target personas are noted in the personas section in the appraisement section.

* They got here by:
  * 10 points:
    * Referral from an ad
  * 5 points:
    * Our top blog article on how to scope a project, then they read the article for more than 5 minutes.
  * 1 point:
    * Everything else
* Who are they? When a user signs up we usually know:
  * Their business name: no points assigned. However, we look at everyone that comes in and if the business is very large we will sometimes escalate that visitor directly to the sales team.
  * Their type of business:
    * 1 point: Freelancer - we like to know if someone is a freelancer or not
    * 5 points: Marketing - digital or traditional
    * 10 points: Development
    * Enterprise - business is escalated
  * The size of their business - with the use of a 3rd party system
    * 1 point: 1 person
    * 5 points: 2 - 10 people
    * 10 points: 11 - 25 people
    * 15 points: 25 - 100 people
    * More than 100: these groups get automatically sent to our sales team for follow-up every time
  * Their position within the business \(CEO is marked in the middle because they are often freelancers and not really in our target market\)
    * 1 point: Freelancer
    * 2 points: Founder
    * 2 points: CEO - this is often a freelancer, so it is scored lower.
    * 5 points: Project Manager
    * 5 points: Marketing Manager
    * 10 points: CMO
    * 15 points: CTO
* Is their use of the system indicating that they need the system?
  * Did they start a new project?
    * 5 points: yes
  * More than one new project?
    * 5 points: yes
  * Did they use a template?
    * 5 points: small business template
    * 10 points: complex/development template
  * Did they add their teammates?
    * 1 point per teammate
  * Did they send a contract out to a customer?
    * 10 points: yes

When we take a look at the totals, we can see the system groups itself.

### Scenario 1

| Action | Points | Running Total |
| :--- | :--- | :--- |
| Got here from the blog | 5 | 5 |
| Business Type: Freelancer | 1 | 6 |
| Size of business: 1 | 1 | 7 |
| Position: Founder | 3 | 10 |
| Action: Started a new project | 5 | 15 |
| Action: Small business template | 5 | 20 |
| Total |  | 20 |

### Scenario 2

| Action | Points | Running Total |
| :--- | :--- | :--- |
| Came in from ad | 10 | 10 |
| Business Type: Marketing | 5 | 15 |
| Size of business: 7 | 5 | 20 |
| Position: Project Manager | 3 | 23 |
| Action: Started a new project | 5 | 28 |
| Action: Small business template | 5 | 33 |
| Action: Added 3 team members | 3 | 36 |
| Action: Sent contract to user | 10 | 46 |
| Total |  | 46 |

### Scenario 3

| Action | Points | Running Total |
| :--- | :--- | :--- |
| Came in from blog article | 5 | 5 |
| Business Type: Development | 10 | 15 |
| Size of business: 33 | 15 | 30 |
| Position: Project Manager | 3 | 33 |
| Action: Started a new project | 5 | 38 |
| Action: Complex template | 10 | 48 |
| Action: Sent contract to user | 10 | 58 |
| Total |  | 58 |

### Analysis:

As you can see from these different scenarios, the groups we want get pushed up fast. Sales team members can work through top people first, then get to the lower level leads. If someone ranks very high, we can set up some custom notifications that they need to be contacted.

Scenario 1 is definitely a freelancer and should be lower down the list to be contacted. Whereas scenario 3 is a mid-sized development company and should be contacted as soon as possible with a phone call. All we need to do is take a look at our leads list for the day or week, sort them by score start working those leads.

The trick here is not to overcomplicate things. Just add the top indicators and actions, at least in the beginning. As time goes by and you have more data, add more indicators or play around with other triggers, but make it simple to start.

### Putting together Lead Scoring, SaaS email campaigns and sales

In our scenarios, you can see that there is a pretty big jump between the first user, the Freelancer, and the second two groups. This jump makes it easy for sales team members to work the list. It also makes it easy to create other automations. For example, you could set an automatic action in your CRM for any user that comes in with a score over 60 to call or send a personal email.

You could also set up automated emails to users that rank at a 30 or below that help them understand why they need the system as lower level users often fall into the first couple sections of the buying cycle.

{% hint style="success" %}
**PROTIP:** Lead scoring took me a long time to get figure out. It wasn’t that important when we first got started, but when we started to grow it became important fast. People need to know what to do first, what’s most important, and what their processes are for different scenarios. If you set up a good lead scoring system it can make a big difference in how well and fast you process users and make sales.
{% endhint %}

