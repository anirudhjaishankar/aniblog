---
title: "React Redux: Part 1"
date: 2023-06-02T02:00:00+05:30
draft: false
author: Anirudh J
tags: ["React", "Technical", "Redux", "Cheatsheet"]
weight: 1
alias: ["/react-redux-part1"]
---
## Preface
In this two part blog we are going to see what redux is and why, when and how we should use it in our react projects (Please feel free to reachout to me if you feel any part of this blog is wrong).

## Introduction
Redux is a state management library. In common man's terms it is used to keep states "global" so that it can be easily used by other components.

## Why
One of the major pain points for react developers is trying to pass some data between two/more unconnected components. React has a Parent-Child data passing model. This is good for most cases but when you need to pass data between two sibling components, its not possible unless we lift the state to their common parent.

![sharing state between child](images/sibling-state-exchange.jpg)
