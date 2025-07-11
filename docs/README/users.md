Jump to Content

User Documentation

* * *

Developer HubKnowledge BaseLog In

User Documentation

Developer HubKnowledge BaseLog In

User Documentation

Users

Users

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

Users
=====

Understanding all the concepts related to users in WebEngage

Suggest Edits

The following section has been designed to help you understand the different types of users, user attributes and their applications across your WebEngage dashboard. Let’s start with the basics.

Who is a User?


------------------

> 📘
> --
> 
> At WebEngage, anybody who has interacted with your business at least once is called a _User._  
> This definition includes visitors who interact with your mobile app, website, other online platforms and offline avenues.

**This brings us to the question, how does WebEngage detect users?**

It’s pretty simple, actually. Once you connect your platforms _(app, website, CRM, server)_ with your WebEngage account, we automatically start detecting and gleaning basic information about your users in real-time.

All this data gets populated across the following sections of your dashboard:

*   Users _(Basic information related to the user like location, browser, App ID, OS and so on)_
*   Events _(General activity of users like login, logout, app install, app uninstall, session started, session ended and so on)_

Additionally, you can manually upload historical user details or offline user details via the _Data Management_ section of your dashboard. This way, you’ll have all your user data in one place.

### 

Unknown and Known Users

Depending on the kind of information shared by a user on your app or website, they are classified into - _Unknown_ or _Known._

You can think of _Unknown Users_ as ‘Anonymous Users’ and _Known Users_ as ‘Identified Users’. Just like you would use details like a user’s _email address, phone number or customer ID_ to identify your users - so does your WebEngage dashboard. These details are called _Unique Identifiers_ in WebEngage and can be custom defined by you when setting up your account.

#### 

Unique Identifier

A unique identifier is a piece of information generally shared by the users themselves or attributed by you to each user, helping you identify them.

For example, if you define _email address_ as the unique identifier for your account, then all users who have shared their email address on your app/website will become _Known Users._ And users who are yet to share their email address will be treated as _Unknown Users._

> 🚧
> 
> How to Define Unique Identifier
> 
> 
> -------------------------------------
> 
> Please refer to, _Identifying Users_ for step-by-step instructions on how you can set this up for your account. We recommend that you enlist the help of a member of your tech team to execute this.

User Attributes


-------------------

The term _User Attribute_ refers to all the details attached to a user which help us understand their channel preferences, technological preferences, personal details, spending patterns and so on - painting a complete picture of who they are.

These details play an important role in understanding user personas - allowing you to create highly targeted and personalized communication strategies. When using your WebEngage account, you will notice that user attributes have been bucketed into the following types:

### 

System Attributes

These are minute details that the system or WebEngage automatically gleans for all the users who interact with your app and website. So, generic details like a user’s _gender, date of birth_ and so on are called system attributes.

Here's a list of all the system attributes gleaned by us. _(This means you don’t need to worry about tracking all this data!)_

### 

Custom Attributes

These are minute details that any business, like yours, can custom define for their users. This could be any kind of data, such as:

*   Reward Points
*   Customer ID
*   Subscription Renewal Date
*   Customer Type _(Silver, Gold, Platinum)_ and so on.

> 🚧
> 
> How to Define and Pass Custom Attributes to your WebEngage Account
> 
> 
> ------------------------------------------------------------------------
> 
> Please refer to our _tech documentation_ for step-by-step instructions on how you can set this up for your account. We recommend that you enlist the help of a member of your tech team to execute this.

User Profiles


-----------------

A user profile is a comprehensive file which contains all the details related to each user that has ever interacted with your business. Irrespective of whether the users are _Unknown_ or _Known,_ their user profiles contain details against all the system attributes and custom attributes being tracked for your account.

With reference to the example above, If an unknown user shares their email address on a later date, then they will become _Known Users_ and all their existing details and behavioral history will be merged with their new _Known User profile._

Each user profile is a treasure trove of data designed to give you deeper insights into your users’ needs, preferences, and behavior. These details have been bucketed into 5 categories;

**1\. Basic Information**

This section includes the basic details of a user, su

*   Contact information _(name, email address, phone number)_
*   Their activity _(first seen, last seen, total sessions, date of identification, last location)_
*   The source through which you have acquired the user _(channel, campaign name, landing page, referrer)_
*   The segments that are currently included in
*   Details of the most recent campaigns they have interacted with

**2\. Attributes**

You can think of attributes like the smaller details related to a person, which give us cues about their personality, preferences, and background. Hence, this section will include details like a user's:

*   Birthday
*   Marital status
*   Purchase history
*   Reward points
*   Date of birth
*   Gender
*   Educational background

**3\. Devices**

Now let’s understand the concept of ‘devices’. Just like you would refer to a mobile phone, tablet  
or desktop as a device - so does your WebEngage dashboard. Thus, the devices section of a user profile contains details of the devices which have been used to interact with your app or website.

Hence, this section has further been divided into the following subsections:

*   Web
*   Android
*   iOS

Under each subsection, you will find more details about the devices being used by your users, such as:

*   Device ID
*   Browser details
*   Total sessions
*   Date of the first session,
*   Date of last interaction and so on.

**4\. Channels**

In marketing lingo, a channel would typically refer to any channels of communication like _push messaging, in-app messaging, SMS, web pop-ups, web surveys, web push, email_ and so on.

Similarly, even your WebEngage dashboard refers to these as channels.

Hence, under this section, you will see a breakdown of all channels of engagement listed in your dashboard against several parameters, such as:

*   A user’s reachability
*   The total number of messages sent through a campaign
*   The total number of campaigns sent
*   Number of conversions
*   The last message received by the user

**5\. Events**

> 🚧
> 
> Detailed Read on Events
> 
> 
> -----------------------------
> 
> Please refer to _Events_ for a detailed understanding of the concept of Events in WebEngage and its application across your dashboard.

Any actions performed by users across your app and website are called events. For example, let’s say that you have an e-commerce app which requires users to perform certain actions, like;

*   Select a category
*   View a product
*   Add it to the cart
*   Complete checkout

All these actions are called _events._ So, you can think of events as behavioral data, which helps you keep track of what your users are doing.

Thus, the events section of a user profile will show you a list of all the latest events performed by the user, with more details attached to each like;

*   Date and time
*   Location
*   Browser
*   Campaign name
*   Screen name
*   Page name

> 🚧
> 
> Analysing User Profiles
> 
> 
> -----------------------------
> 
> All the sections of a user profile and the data points stored under each have been discussed in further detail under _Analysing User Profiles._

Updated about 2 years ago

* * *

So, what's next?

We hope this has warmed you up to all the concepts related to users and their application across your WebEngage dashboard. Let's walk you through how you can analyse users to gain deep insights into their preferences and personas.

*   Analyzing Users

*   Table of Contents
*   *   Who is a User?
        *   Unknown and Known Users
    *   User Attributes
        *   System Attributes
        *   Custom Attributes
    *   User Profiles