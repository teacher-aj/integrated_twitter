# Class Twitter Capstone Project

Welcome to the **Class Twitter Capstone Project**!\

<img width="348" height="348" alt="image" src="https://github.com/user-attachments/assets/c6340d21-4076-4bab-a2f6-f8e6807c59a9" />

Over the next three weeks, you will work in teams to build a **larger,
more realistic version of Twitter** using Python.

This project is designed to feel like a **real startup**: - Different
teams own different features - Everyone works on the same codebase -
Everything must work together

------------------------------------------------------------------------

## Project Goal

By the end of this project, we will have: - A shared Python-based
Twitter-style app - Multiple features built by different teams - A
single "source of truth" for tweets and users - A working feed that
updates as new content is added

You are **not** building separate projects.\
You are building **one product together**.

------------------------------------------------------------------------

## Big Idea

> Real software is not built by one person.\
> It is built by teams who agree on how their code connects.

This project is about: - Writing clear functions - Respecting shared
data formats - Debugging integration problems - Communicating with other
teams

------------------------------------------------------------------------

## Repository Structure

    /data
      users.csv
      tweets.csv
      likes.csv

    /core
      data_loader.py
      models.py

    /features
      feed/
      profiles/
      engagement/
      search/
      moderation/

    /app
      app.py

    README.md

Do **not** rename or delete shared files unless approved.

------------------------------------------------------------------------

## Shared Data Rules (VERY IMPORTANT)

All teams must respect the shared data format.

### Required Files

-   `users.csv`
-   `tweets.csv`
-   `likes.csv`

### Rules

-   You may **add columns**
-   You may **not remove or rename existing columns**
-   All file reads/writes must go through shared helper functions

Breaking these rules will break the app.

------------------------------------------------------------------------

## Function Contracts

Your code must assume these functions exist and work as described.

``` python
load_users()
load_tweets()
save_tweets(df)
get_user_by_id(user_id)
```

You may add new functions, but you may not change how shared ones
behave.

------------------------------------------------------------------------

## Team Roles

Each team owns one feature area.

### Example Teams

-   Feed Team (home timeline logic)
-   Profiles Team (user pages)
-   Engagement Team (likes / retweets)
-   Search & Discovery Team
-   Moderation & Safety Team
-   App / UI Team

You are responsible for: - Your feature working - Your feature not
breaking others - Clearly documenting your functions

------------------------------------------------------------------------

## How We Work on GitHub

We are **not using git commands**.

Instead: 1. One person edits a file at a time 2. Changes are uploaded
manually through GitHub 3. Always pull the latest version before editing
4. Write clear commit messages

Example: \> "Added function to count likes per tweet"

------------------------------------------------------------------------

## Feature Freeze

After **Week 2**, no new features may be added.

Only: - Bug fixes - Cleanup - Documentation

This mirrors real software development.

------------------------------------------------------------------------

## How You'll Be Assessed

You will be evaluated on: - Correctness of your feature - Respecting
shared interfaces - Code clarity and comments - Collaboration and
communication - Reflection on what worked and what didn't

------------------------------------------------------------------------

## Reflection Questions (End of Project)

You will answer: - What broke during integration? - What was harder than
expected? - How did your team coordinate with others? - What would you
redesign if you had more time?

------------------------------------------------------------------------

## 🎯 Final Note

This project will feel messy at times.\
That is **normal**.

If everything worked perfectly the first time, it wouldn't be real
software.

Good luck and build responsibly
