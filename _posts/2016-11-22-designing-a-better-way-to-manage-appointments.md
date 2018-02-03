---
layout: post
title: "Designing a better way to manage appointments"
date: 2016-11-22 03:37
author: aymeric
wordpress_id: 1748
navigation: True
class: post-template
comments: true
categories: [Product]
tags: []
---
When I started working on WeekPlan, the focus was more on tasks rather than events (tasks with a start time). As WeekPlan grew, it started to attract more people with event heavy schedules. I want to allow these users to manage their schedule while keeping it as simple as possible to the people who rely on tasks more than events.<!--more-->


## Current state of the art


One of the most requested feature for WeekPlan is the ability to see a day like in a classic calendar, hour by hour. I personally think that the classic calendar view can be wasteful:

![Wasted space in calendar view](/assets/images/uploads/1748-image-7.png)

So I started looking at existing alternatives.


### Duration based


Some apps display tasks based on their duration. This ’is nice for a

![Tasks by length](/assets/images/uploads/1748-image-8.png)


### Sorted by time


This alternative is generally more compact but less visual. It is hard to figure out how long is a task and where are the available slots in the day:

![List of events](/assets/images/uploads/1748-image-9.png)


## WeekPlan take #1


In WeekPlan, the events are shown like normal tasks except that a grey background color shows you when they start and how long they last for visually:

![Event visualization in WeekPlan](/assets/images/uploads/1748-image-10.png)

If you drag a task after “WeekPlan marketing catchup”, the task will automatically be assigned the start time “15:00”.

Although it is an improvement over what was orginally available in WeekPlan, it doesn’t make it easy to set a specific start time. You have to open the edit dialog and change the start time value there.


## WeekPlan take #2


We are currently rewriting the user interface of WeekPlan and we took the opportunity to improve on our design by doing two things.

![New visualization of events from WeekPlan](/assets/images/uploads/1748-image-11.png)

First we separate events from tasks and second, we introduce the time bar.

The time bar shows you how your day looks like at a glance and allows you to easily schedule a task in the day by dragging it onto the time bar:

![](https://i.gyazo.com/fce6fa57860ce93359177277ac93181d.gif)

We are excited with this new way to handle appointments and wanted to give you a sneak peek of the upcoming version of WeekPlan.
