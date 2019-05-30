---
layout: project
title: Omega Airlines
date: December 16, 2018
category: Software

buttons:
  - name: github
    url: https://github.com/cestrrada/OmegaAirlines
    color: btn-light
    icon: fab fa-github

version: 1.0
featured: omega/featured.jpg
description: An Android pseudo-application that allows users to book and manage their flight reservations.
---

### Overview
Omega Airlines is an Android pseudo-application for booking, viewing and cancelling flight reservations as well as managing an airline system as an administrator. It was created as a final project for my Software Design class at CSU Monterey Bay after 4 months of having familiarized ourselves with Java and Android Studio.

#### Features
- Account sign in and registration
- Reservation manager that displays the user’s flights
- Ability to search for any available flights in the database
- Ability to book reservations (with user authentication)
- Admin: Add and remove flights from the database
- Admin: View system logs (e.g. login attempts, reservations, cancellations, etc.)

#### How It Works
Using Java, Android Studio and SQLite databases, the application greets users with a simple log in screen and an option to create an account.

Once logged in, users are shown their dashboard, where they can interact with the bottom navigation bar to view their existing reservations or search for a new one. A user with administrative privileges can also view system logs, view a complete list of all available flights and create new flights to add to the database.

#### Challenges
One of the biggest challenges I faced while working on this project was familiarizing myself with Android’s API, specifically Fragments and Recycler Views.

In order to implement the bottom navigation bar I had initially envisioned, I quickly realized I would need to learn about Fragments. Figuring out how to pass data between Activities and Fragments proved difficult but ultimately was successful.

I had also realized that Recycler Views were going to be a large part of the app and faced similar challenges here in passing information from the the database and Fragments to a Recycler View adapter and displaying the list items to the user.

#### How to Install
- Download and unzip the file below onto your Android device.
- Requires Android 7.0 Nougat (API 24) or higher.

##### Credits
[Airplane](https://thenounproject.com/term/airplane/100813){:target="_blank"} by Simon Child, The Noun Project.