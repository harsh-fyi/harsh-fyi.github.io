---
title: 8 Misconceptions in System Design Interviews
date: 2020-02-12 23:57:00 -08:00
tags:
- sample post
- code
description: Learn how to do this
comments: false
share: true
layout: post
---

## #1. “System Design interviews have a fixed format”

In coding interviews, you are given a problem and you find a solution. It's more or less objective. System Design is far from objective.

There's no right answer. Or a right direction. If that sounds confusing, you're not alone.

System Design interviews are meant to be discussions. Each interviewer wants something different.

How different? Here's an example:

* Interviewer 1: Wants a backend with a single machine.

* Interviewer 2: Wants a scalable backend with 1000s of machines.

Here are a couple more:

* Interviewer 1: Wants you to write pseudocode for your web server's logic

* Interviewer 2: Wants to know how your app server will handle thousands of requests/second

Interviewer 1: Gives you a clear set of features
Interviewer 2: Expects you to articulate features

## #2. “I should list a lot of features”

Let's say you're asked to design Facebook. Here's a common first instinct:

**"Do we want a home feed with intelligent recommendations?"
"Do we want privacy features like access controls?"
"Do we want to upload photos with tagging?"**

The instinct is to list as many features as possible. We think - this will impress the interviewer. Wrong.
The interviewer is not looking for your product design skills. They're looking for your system design skills.
So any features you list won't matter in the interview.

Product Design vs System Design

The goal is to get to the System. And for that, you need to quickly decide on features and get them out of the way.
The best way to do this - narrow down features as much as possible. List only the essential features.

![n-queens-problems.png](/uploads/n-queens-problems.png)

For example, with Facebook:

1. Users have a list of friends

2. Each user has a wall

3. People can write on a user's wall.

That's it. No photos, no home feed. Even with those 3 features, the system is complicated enough for hours of discussion.