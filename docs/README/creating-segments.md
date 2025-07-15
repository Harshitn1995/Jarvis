---
layout: default
title: Creating Segment
---

<button onclick="window.history.back()">🔙 Go Back</button>

# 🧱 Creating a Segment in Jarvis

Welcome to **Jarvis's guide** to getting started with **Creating Segment**.

<aside class="toc">
  <h2 style="text-align: center;">📑 Table of Contents</h2>
  <ul>
    <li><a href="#step-1-name-your-segment">📝 Name Your Segment</a></li>
    <li>
      <a href="#step-2-define-the-rules-of-segmentation">🧩 Define the Rules</a>
      <ul>
        <li>
          <a href="#user">👤 2.1 User</a>
        </li>
        <li>
          <a href="#behavioral">⚙️ 2.2 Behavioral</a>
        </li>
        <li><a href="#technology">💻 2.3 Technology</a></li>
      </ul>
    </li>
    <li><a href="#step-3-preview-segment">🔍 Preview Segment</a></li>
    <li><a href="#-next-steps">🎯 Next Steps</a></li>
  </ul>
</aside>

---

## ✉️ Let's Get You Started

Jarvis allows you to create **live segments** of users using behavioral data, user attributes, and tech filters.

> 🚧 **Must Read**
>
> Make sure you’re already familiar with **Users** and **Events**, as these are foundational to segmentation.

Let’s walk through how to create a simple use-case segment:

> 👍 **Use-case:**
>
> Target users located in Mumbai, India who **added products to cart** but **didn’t purchase in the last 7 days**.

---

Creating segments in Jarvis is like building with Legos: pick the right blocks (rules), stack them, preview them—and you’re good to go! If you don’t like the result, reset and start over.

---

## Step 1: Name Your Segment {#step-1-name-your-segment}

🖋️ Start by assigning your segment a **unique, descriptive name** to help identify its purpose later.

---

## Step 2: Define the Rules of Segmentation {#step-2-define-the-rules-of-segmentation}

Jarvis segmentation is divided into 3 main rule types:

- 👤 **User** (who they are)
- ⚙️ **Behavioral** (what they did/didn’t do)
- 💻 **Technology** (what devices/OS they use)

Each rule type can include multiple filters using **AND/OR** logic.

Let’s deep-dive into each section 👇

---

## 2.1 👤 User {#user}

This section lets you segment based on system and custom **user attributes** like:

- [Visitor Type](#visitor-type)
- [Last Seen](#last-seen)
- [Created On](#created-on)
- [Geo Filtering](#geo-filtering)
- [User Attribute](#user-attribute)
- [First Acquisition Source](#first-acquisition-source)
- [User IDs](#user-ids)
- [Reachability](#reachability)

---

### Visitor Type {#visitor-type}

🎯 Filter users based on frequency of visits:

- All Users
- New (1 session)
- Returning (2+ sessions)
- Session count using custom operators (equal to, less than, etc.)

---

### Last Seen {#last-seen}

🕒 Target users based on last interaction date. Supports:

- After/Before/Within custom time frames
- Present or Not Present

---

### Created On {#created-on}

📅 Filter by when a user was first acquired. Supports similar logic as "Last Seen."

---

### Geo Filtering {#geo-filtering}

🗺️ Include/Exclude users based on **Country > Region > City**.

- Combine using “Any” (include) or “None” (exclude)
- Limit to 3 locations max

---

### User Attribute {#user-attribute}

🔍 Combine custom & system attributes:

- AND/OR logic supported
- Example: Country = Singapore AND Loyalty Points >= 5000

> 📘 System attributes include:
>
> - Country, Region, City
> - Name, Birth Date, Gender
> - Email, Hashed Email
> - Phone, Hashed Phone
> - Custom attributes vary per account

---

### First Acquisition Source {#first-acquisition-source}

🧭 Filter users based on how they first discovered you:

- For **Web**: Referral, Direct, Email, Organic, Social, Display, Campaign, etc.
- For **App**: AppsFlyer, Adjust, Branch integration required

---

### User IDs {#user-ids}

🔢 Create niche segments by filtering specific User IDs using:

- Equals, Starts with, Ends with, Contains, Regex, etc.

---

### Reachability {#reachability}

📡 Include/Exclude users based on channel accessibility:

- Push, Email, SMS, Web Push, WhatsApp

> 👍 Use-case: Segment users **not reachable on Push** and engage via Email or SMS instead.

---

## 2.2 ⚙️ Behavioral {#behavioral}

Use events to target users based on actions they've **taken** or **not taken**.

---

### Understanding Behavioral Conditions {#understanding-behavioral-conditions}

You can define two types of rules:

- ✅ **Users who DID** these events
- ❌ **Users who DID NOT** do these events

Use **AND/OR** logic between the conditions.

> 👍 Use-case: Segment users who:
>
> - Purchased at least once
> - Opened app in last 2 weeks
> - Haven’t purchased in last 2 weeks

---

### Configuring Behavioral Rules {#configuring-behavioral-rules}

Each event can include **event attribute filters** to refine conditions further.

---

### Step 1: Select Event {#step-1-select-event}

🧩 Choose any **System, Custom, or Campaign** event.

---

### Step 2: Add Event Attributes Filters to Event {#step-2-add-event-attributes-filters-to-event}

🔧 Add filters like:

- Cart Value > $100
- Country = United States
- City = Sacramento

> 👍 Use-case: Segment users with cart value > $100 in Sacramento **who didn’t checkout**.

---

### Step 3: Specify Event Occurrence Frequency/Recency {#step-3-specify-event-occurrence-frequency-recency}

📅 Add time-based rules like:

- At least once
- Only once
- No. of occurrences (with condition)
- Most recent / least recent event time

---

## 2.3 💻 Technology {#technology}

Target users by device/OS:

- **Android**
- **iOS**
- **Web**

> 👍 Use-case: Show rich push notifications to only Android & iOS users on the latest app version.

**Attributes include:**

- App Install Date, Time Spent, Version
- OS/Browser/Device Type
- Manufacturer, Model, etc.

---

## Step 3: Preview Segment {#step-3-preview-segment}

📊 Once you've defined rules, use the right-hand **Preview Pane** to see:

- **Total Users**
- Known / Unknown Users
- Reachable via any channel

> 🚧 **Note:** Complex segments may take time to build. You’ll see "⏳ In Progress" until complete.

---

## ✅ Next Steps

Once your segment looks good:

1. Click **Save** (top right)
2. Your segment will now appear in the **List of Segments**
3. Use it in campaigns, journeys, or analytics!

What will your **first segment** be?

---

📝 _Last updated over 1 year ago_
