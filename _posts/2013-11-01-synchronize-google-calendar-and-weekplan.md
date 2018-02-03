---
layout: post
title: "How to set the synchronization between Google Calendar and WeekPlan"
date: 2013-11-01 07:42
author: aymeric
wordpress_id: 807
navigation: True
class: post-template
comments: true
categories: [Product]
tags: [zapier]
---


**UPDATE: this is no longer the recommended way to set up synchronization between Google Calendar and WeekPlan. We have built an in-app integration instead. You can access from within your workspace settings.**


&nbsp;


Simple Google Calendar synchronization can be set if you upgrade your WeekPlan account to PRO. This is a little tutorial to show you how to see all the tasks you create inside WeekPlan in Google Calendar.


<!--more-->


1. Create a Zapier.com account


Zapier is a third party product that WeekPlan uses to connect to 100s of other services.


Simply fill in the form here: [https://zapier.com/app/signup](https://zapier.com/app/signup)


2. Once you are logged in, click on the “Create a Zap” button:


![Create new Zap](http://54.173.16.9/wp-content/uploads/2013/11/image.png "Create new Zap")


3. Select Week Plan as the Trigger Service, and Google Calendar as the Action Service, like so:


![Pick your Trigger and Action](http://54.173.16.9/wp-content/uploads/2013/11/image1.png "Pick your Trigger and Action")


In the “When this happens” field, pick “New Task” to notify Zapier when a new task is created in WeekPlan.


In the “Do this” field, pick “New Detailed Event”.


When ready, click **Continue**.


4. You will then be asked to enter your WeekPlan account.


![Select a WeekPlan account](http://54.173.16.9/wp-content/uploads/2013/11/image2.png "Select a WeekPlan account")


A dialog box should open to ask you to fill in your WeekPlan credentials:


![Enter your WeekPlan credentials](http://54.173.16.9/wp-content/uploads/2013/11/image3.png "Enter your WeekPlan credentials")


Note: You can get your Api Key here: [https://app.weekplan.net/#view=AccountSettings](https://app.weekplan.net/#view=AccountSettings)


![Data synchronization box](http://54.173.16.9/wp-content/uploads/2013/11/image4.png "Data synchronization box")


Click “Continue” when you are done.


5. You will then be asked to select your Google Calendar account:


![Select a Google Calendar account](http://54.173.16.9/wp-content/uploads/2013/11/image5.png "Select a Google Calendar account")


The procedure should be fairly straight forward so I won’t go in the details.


6. Next, you will be asked to select which workspace you want to synchronize:


 ![Pick a workspace](http://54.173.16.9/wp-content/uploads/2013/11/image6.png "Pick a workspace")


7. And finally, you will be asked to map the fields from WeekPlan into the Google Calendar fields.


Let me show you how to do it.


First you choose the calendar you want the WeekPlan tasks to appear into. Next you want to map the Text and the Notes fields like so: (click on the blue weekplan icon to pick a field)


![Map the fields](http://54.173.16.9/wp-content/uploads/2013/11/image7.png "Map the fields")


Then for Start Date &amp; Time, and End Date &amp; Time, make sure you pick the right fields:


![Map the fields](http://54.173.16.9/wp-content/uploads/2013/11/image8.png "Map the fields")


&nbsp;


UPDATE 12AUG14: Don’t forget to tell Google Calendar which events are all day events:


![All day events field](http://54.173.16.9/wp-content/uploads/2014/08/image6.png "All day events field")


8. That’s it! Zapier allows you test your new Zap by clicking the Send button. If everything is ok, you should see your task in your Google Calendar.


![Try out your Zap](http://54.173.16.9/wp-content/uploads/2013/11/image9.png "Try out your Zap")


&nbsp;


If you want to receive the events you create inside Google Calendar in WeekPlan, you need to create another zap and do the procedure again but using Google Calendar as the Trigger service and WeekPlan as the Action service. If you have any question, please leave a comment on this page and we will come back to you.

