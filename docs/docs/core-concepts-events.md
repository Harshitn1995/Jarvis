Jump to Content

User Documentation

* * *

Developer HubKnowledge BaseLog In

User Documentation

Developer HubKnowledge BaseLog In

User Documentation

Events

Events

Search

WebEngage Basics
----------------

*   Preface
*   Users
*   Events
    *   Understanding Events & Event Attributes

Analytics
---------

*   Dashboards
*   Analyzing Users
    *   Analyzing User Profiles
*   Analyzing Events
*   Paths
*   RFM Analysis
*   Funnels
    *   List of Funnels
    *   Creating Funnels
    *   Analyzing Funnels
    *   Modifying Funnels
    *   Help Center
*   Cohorts
    *   Cohort Analysis: Use-cases
    *   Analyzing Cohorts
    *   Help Center
*   Uninstalls
*   Live

Segments
--------

*   Getting Started
*   Live Segments
    *   Live Segments Hub
    *   Creating Live Segments
    *   Analyzing Live Segments
    *   Modifying Live Segments
*   Lists
    *   Lists Hub
    *   Creating Lists
    *   Analyzing Lists
*   Refreshing Lists
*   Predictive Segments
*   Help Center

Data Platform
-------------

*   Data Management
    *   Defining Data Model
    *   System Attributes
    *   User Profile Attributes
    *   Custom Events
    *   Revenue Mapping
    *   Personally Identifiable Information (PII)
    *   Conversion Card Setting
*   Upload Data
    *   Upload User Data
    *   Upload Events Data
*   Engagement Score
*   Web Integration
*   Android Integration
*   iOS Integration
*   Rest API
*   Webhooks
*   Catalogs and Recommendations
    *   Collections
*   Custom Alerts

Campaign Manager
----------------

*   Key Concepts
    *   Channels & Channel Reachability
    *   Campaigns & Its Types
    *   Preface
    *   Conversion Tracking
    *   Control Groups
    *   Revenue Tracking
    *   Campaign & Channel Performance Indicators
    *   Campaign Variations and Multivariate Testing
    *   Frequency Capping
    *   DND Hours
    *   Queueing
    *   Throttling (Message Rate-Limiting)
    *   Send Intelligently
*   Engagement Overview
*   Push
    *   Channel Configuration
    *   List of Campaigns
    *   Creating Push Campaigns
    *   Creating Transactional Push Campaigns
    *   Analyzing Push Campaigns
    *   Analyzing Push Overview
    *   Push Layouts: Image & Text Guidelines
    *   Creating Dynamic Push Experiences Using Key-Value Pairs
    *   Help Center
*   SMS
    *   SSP Integration
    *   List of Campaigns
    *   Creating SMS Campaigns
    *   Creating Transactional SMS Campaigns
    *   Analyzing SMS Campaigns
    *   Analyzing SMS Overview
    *   Help Center
*   RCS
    *   RSP Integration
    *   List of Campaigns
    *   Creating RCS Campaigns
    *   Accessing and Understanding RCS Campaigns
    *   Analyzing RCS Channel Overview
    *   Analyzing RCS Campaign
    *   Rich Communication Service Template Creation
    *   Help Center
*   Web Push
    *   Channel Configuration
    *   List of Campaigns
    *   Creating Web Push Campaigns
    *   Analyzing Web Push Campaigns
    *   Analyzing Web Push Overview
    *   Web Push Layouts: Image & Text Guidelines
    *   Help Center
*   Email
    *   ESP Integration
    *   List of Campaigns
    *   Creating Email Campaigns
    *   Creating Transactional Email Campaigns
    *   Using the Drag & Drop Editor
    *   Analyzing Email Campaigns
    *   Analyzing Email Overview
    *   Image & Text Guidelines
    *   Help Center
    *   AMP Emails
    *   AMP Email Use Cases
    *   Add Brand Logo to Emails
*   WhatsApp
    *   WhatsApp Integration
    *   List of Campaigns
    *   Creating WhatsApp Campaigns
    *   Creating Transactional WhatsApp Campaigns
    *   Accessing and Understanding WhatsApp Campaigns
    *   Analyzing WhatsApp Campaign
    *   Analyzing WhatsApp Channel Overview
    *   Help Center
*   Facebook
    *   Facebook Business Integration
    *   Help Center
*   Google Ads
*   TikTok
*   Journeys
    *   List of Journeys
    *   Journey Creation Guide
    *   Journey Creation: How It Works
    *   Analyzing a Journey
    *   Analyzing Journeys' Overview
*   Relays
    *   Getting Started
    *   Catalog Based Relays
*   Reports
    *   List of Scheduled Reports
    *   Schedule Channel Performance Reports
    *   Understanding Report Stats
*   Configurations
    *   DND Hours
    *   Throttling
    *   Frequency Capping
    *   Custom Domain
    *   Configure Control Groups
    *   UTM Parameters

Website Personalization
-----------------------

*   Web Personalization: In-line Content
    *   List of Campaigns
    *   Creating Web In-line Content Campaigns
    *   Analyzing Inline Web In-line Campaigns
    *   Analyzing Web In-line Overview
*   On-site Notifications
    *   Advanced Targeting
    *   List of Campaigns
    *   Creating On-site Notifications
    *   Analyzing On-site Notifications
    *   Modifying On-site Notifications
    *   Notification Settings
*   On-site Surveys
    *   Advanced Targeting
    *   List of Surveys
    *   Creating Surveys
    *   Analyzing Responses
    *   Modifying Surveys
    *   Survey Settings

App Personalization
-------------------

*   In-app Notifications
    *   In-app Message Targeting
    *   List of Campaigns
    *   Creating In-app Campaigns
    *   Analyzing In-app Campaigns
    *   Analyzing In-app Overview
    *   In-app Layouts: Image & Text Guidelines
    *   Help Center
*   App In- Line Content
    *   Getting Started
    *   Understanding Properties
    *   List of Campaigns
    *   Creating App In-line Campaigns
    *   Accessing and Understanding App In-line Campaigns
    *   Analyzing App In-line Campaigns
    *   Analyzing App In-line Overview
    *   FAQ

Settings
--------

*   Audit Log
*   Role-Based Access Control

Events
======

Preface: Different Users, Different Behaviour, Different Needs

Suggest Edits

The primary goal of any modern marketer, working for an online business is to create great customer experiences and keep them coming back for more. This ties back to your users, how they perceive your brand and how they interact with your product.

As marketers, we are well aware of the fact that different kind of users have different needs and are capable of responding to the same message in different ways. Such varied human behavior is what has led marketers around the world to adopt personalized and contextual lifecycle communication.

The idea is to give each user what they want when they want it - delivered through a preferred channel of communication, as a response to their behavior.

Sounds great, right?

But managing the expectations of millions of users, every day, is no easy task. It involves keeping track of each user, observing their behavior, understanding their needs and engaging with them accordingly.

So, how do you make this possible?

### 

Understanding Your User’s Lifecycle

The first step to delivering contextual communication is to understand the mental, emotional and physical states that your users experience while interacting with your product.

At this point, any experienced marketer will be quick to point out that there is no way (yet) to quantify the mental and emotional states experienced by their users. _(Detailed read: Marketer's User Empathy Model)_

True.

But what you can quantify (track and analyze) is the physical state experienced by a user throughout their lifecycle.

You can think of the physical state as the actions performed by users when interacting with your app and website. These actions could be anything like;

*   searching for a product
*   applying filters
*   viewing product details
*   making a purchase and so on.

So, if we were to break down a typical online user’s behavior into stages, it would look something like this:

A typical digital user's lifecycle (Click to enlarge)

At each stage, users perform various actions and evidently, experience different mental and emotional states. This warrants the implementation of differentiated strategies for engaging one-on-one with users at each stage.

### 

Tying Behavioural Data to Everything You Do

The most scientific way to start designing differentiated engagement strategies is to track the behaviour of your users, throughout their lifecycle. Here’s why:

1.  Behavioural data lays the foundation for analysing your users’ actions and creating hypotheses around what they think and feel, as they move from one stage to the next.
    
2.  It’s also the starting point for digging into the possible motivations built into your product or campaigns which push some users to convert faster than the others (or abandon you all together).
    
3.  And lastly, behavioural data plays an essential role in understanding what’s missing from your product or communication - something that could help users make the most of your offerings, faster.
    

> 👍
> 
> Use-case
> 
> 
> --------------
> 
> For example, if you observe that most users take maximum time to move from _Evaluation_ to _Conversion_, then you know that they need some form of motivation, reinforcing their decision to make a purchase.

This motivation could be anything like;

*   Sending a compelling offer, bringing them a step closer to owning a product they’ve been eyeing for a while.
    
*   Showing users how happy other customers feels after purchasing your product/service.
    
*   Making it easier for them to commit to a long-term purchase by offering a time-bound return policy.
    
*   Showing them how your product/service can make a significant contribution to their lives.
    
*   Or, making it easier for them to make a payment and checkout by simplifying your UI.
    

While variables like the message, channel and timing can be guided by a combination of individual user preferences and the details shared with you - the fact that they need external motivation to progress from _Evaluation_ to _Conversion_ becomes indisputable.

**In this sense, all behavioral data doubles up as a source of truth.** It tells you what your users want and helps you gauge the effectiveness of your communication by indicating if it resulted in the desired behavior or not.

At WebEngage, we firmly believe that the success of any consumer business, like yours, is tied to how well you understand your users and their actions. Conceptually, all behavioral data points are called **Events** in your dashboard. And each _Event_ can further be understood in the context of its **Attributes** which includes details like _time, location, device details, price, quantity,_ and so on. This enables you to gain in-depth insights into user interactions and behavior across your app, website, and channels.

Updated almost 6 years ago

* * *

So, what's next?

Let's get you acquainted with all the concepts related to behavioral data or Events.

*   What are Events and Event Attributes?

*   Table of Contents
*   *   Understanding Your User’s Lifecycle
    *   Tying Behavioural Data to Everything You Do