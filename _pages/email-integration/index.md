---
layout: page
title: "Email integration"
date: 2014-04-09 12:37
author: aymeric
wordpress_id: 882
navigation: True
permalink: /email-integration/
class: post-template
comments: true
categories: []
tags: []
---

You can send tasks via email. Here we describe the format.

## Send a list of tasks via email

Sometimes you want to be able to "braindump" a list of tasks.

**From:** Email address you use to log into Week Plan  
**To:** today@hello.weekplan.net   
**Subject:** Ignored  
**Body:**

Task item 1  
Task item 2  
Task item 3

## Send a task (with notes and subtasks) via email

The task can be sent to today or to any list of the parking lot or board.
 
**From:** Email address you use to log into Week Plan  
**To:** todo+*workspaceid*@hello.weekplan.net ([Find the email address here](https://app.weekplan.net/#view=WorkspaceSettings))

If you want to send to a list, you will find the email address in the edit dialog of the list.

**Subject:** &lt;Task name&gt;  
**Body:**

Add your notes here.

[ ] Sub task 1 (must start with [] or [ ])    
[ ] Sub task 2  
[ ] Sub task 3

![Screenshot](http://i.gyazo.com/1e2ad1337275b5b69ec30a7672676435.png)
 
## Send a comment via email

You can reply to the email notifications about a specific task to post a comment on that task.

**From:** Email address you use to log into Week Plan  
**To:** Just reply to an email notification related to a task  
**Subject:** Ignored  
**Body:**

Any text
 
## Send a journal entry via email

You can reply to the coaching emails to post a new journal entry.
 
**From:** Email address you use to log into Week Plan   
**To:** just reply to a coaching email
**Subject:** Ignored  
**Body:**

Any text