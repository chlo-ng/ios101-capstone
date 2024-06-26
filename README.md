# Habit Tracker

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)
5. [Sprint 1](#Sprint-1)
6. [Sprint 2](#Sprint-2)
7. [Sprint 3](#Sprint-3)

## Overview

### Description

An app that allows the user to track their daily habits. Each habit will be represented as a circular progress bar. Logging a completed habit would increase a user's streak, leading to possible achievements. The user can make reminders for themselves if they are important.


### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** Lifestyle
- **Mobile:**
    - Having this format of a daily tracker exceeds a website, because users are able to have a digital journal on their phones
    - Users will also be able to log their habits in real time, which will be saved into the app as well.
- **Story:**
    - The value in this app is that it provides a digital alternative to physical bullet journals, which could be time consuming to some users
    - Users will also be able to use it as a general reminder app,  but with some gamification implemented to help incentivize upkeeping their important habits
    - Since I have multiple friends who are in college, I think I would have a good reaction from my friends if this app were to be released as college students generally get really busy and forget their healthier habits
- **Market:**
    - The potential user base is speculated to be high school to adult women who need to keep track of important habits
    - Could expand to a more general audience as well due to its usability
- **Habit:**
    - It is speculated that an average user would open this app at least once a day because they would have the incentive to log their daily habits
    - An average user would be creating with this app
- **Scope:**
    - This application is estimated to be slightly more challenging than the past labs that we were given because more elements are added such as circular progress bars, achievements and reminders
    - A stripped version that excludes the reminders would still be interesting, because there is an audience who would enjoy seeing their habits displayed for them


## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* The user can **create** a new habit to track
* The user can **log** a completed habit daily
* The user can **delete** a habit
* The user can **view** their list of habits and **track** their progress

**Optional Nice-to-have Stories**

* The user can **make an account**
* The user can **update** a habit
* The user can **receive** achievement awards for logging habits daily
* The user can **write** notes about a habit

### 2. Screen Archetypes

- [ ] Stream: List of Habits
* The user can **view** their list of habits and **track** their progress
* The user can **delete** a habit
- [ ] Creation: Creating a Habit
* The user can **create** a new habit to track
* The user can **delete** a habit
- [ ] Detail: Logging/Updating a Habit
* The user can **log** a completed habit daily
* The user can **update** a habit
* The user can **write** notes about a habit
- [ ] Profile: Achievements Page
* The user can **receive** achievement awards for logging habits daily

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* List of Habits
* Profile

**Flow Navigation** (Screen to Screen)

- [ ] List of Habits
* from tab navigation
* back or save button from Creating a Habit screen
- [ ] Creating a Habit
* clicking a + button from List of Habits
- [ ] Logging/Updating a Habit
* clicking one of the habits from List of Habits
- [ ] Profile
* from tab navigation


## Wireframes

<img src="https://github.com/chlo-ng/ios101-capstone/blob/main/ios%20habit%20tracker.png" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]

## Sprint 1
### Objectives
- [x] Set up 2 custom classes: Habit, HabitCell
- [x] Set up the List of Habits screen
- [ ] Have a button navigate to Creating a Habit
- [x] Set up the Creating a Habit page with input fields

### Demo Video
[Demo](https://www.loom.com/share/50b90e0c907548108c729109eb484612?sid=6f82e4a7-8471-43f0-8b92-a20ce3dc84f3)

### Challenges
Getting started was rockier than I thought it would be, a lot of errors encountered.
But I eventually figured it out and I believe I set a good foundation for the remainder of the app.

### What's Next
Something I didn't achieve this week is making a button that navigates to Create a Habit screen. Instead, I made each table cell clickable and they navigate to Creating a Habit. Before the next sprint, I will make this button to transition smoothly to the next tasks.

## Sprint 2
### Objectives 
- [x] Set up adding a new habit
- [x] Set up updating an existing habit
- [x] Set up deleting an existing habit
- [ ] Set up a skeleton of the Profile page
      
### Demo Video
[Demo](https://www.loom.com/share/3dc262e4e5454a95a99bbb3cc059065c?sid=488a15ba-f469-442c-a5b2-89fcac24e410)

### Challenges
Setting up local storage was a little hurdle, but it worked out!

### What's Next
Something I didn't achieve this week was to set up the profile page. But with the habits set up, there are only a few more things until my final app will be complete!

## Sprint 3
### Objectives
- [x] Navigating between List of Habits and Profile Page
- [ ] Making a Habit as completed onto a calendar view
- [x] Link completed habits to a visualization

### Demo Video
[Demo](https://www.loom.com/share/1589f4e599a7467891ec4a948bfc59d7?sid=02afa085-f521-4b53-b079-10a74e8bb64e)

### Challenges
It was hard to update the habits to be completed - I hit a wall because some values were producing errors saying that they are Optionals, when I did not set them as Optional. But I found a workaround and it worked!

### What's Next
I did not implement the calendar view to show which dates the habit were completed. But the progress view updated by marking the habits as complete! It also doesn't deselect if the date last selected was the current date.
Next up is to make these visually visible and more appealing on the app. 
