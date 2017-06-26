---
layout: post
title: Using Tree Testing to Find Information Architecture Issues
author: jonathan
tags: [information architecture, tree testing]
---

## What is Tree Testing? ##

Tree testing is a way to test that your information architecture (IA) matches the mental models of your users.  It aims to answer the following questions:
* can people easily find information on your website?
* do your menu/category names make sense to your users?
* is information categorized in a way that users expect?

Tree testing is an important IA technique because it _separates the user interface from the information structure._  During a tree test, users do not interact with the user interface; they navigate using only links.  By separating out the structure from the interface, you can determine if an issue is caused by the information architecture (e.g. people don't understand your category names, your heirarchy doesn't match how users think about the information, etc.) or by the navigational components and UI layout.  Let's look one of the most common issues clients have with their websites.

## People Aren't Visiting An Important Part Of My Site! ##

This issue can be caused by information architecture, UI design, or both. Figuring out which is very important: if you 'guess' and guess wrong, it can be very costly in terms of both time and money.  For example, if your client thinks that users aren't visiting a page enough due to the navigation not highlighting it enough, they may ask their developers to redesign the site in a way that puts more focus on it (through placement, colour, perhaps a new navigation system, etc.).  This can have numerous unintended consequences such as reducing traffic to currently well-performing parts of the site, and it may not solve the issue.  This kind of knee-jerk reaction based on gut feelings can be very expensive and leave you in the same situation you started in.

It can be an IA issue:
* users might not understand the category names you've chosen, so they are never navigate to the desired categories (a labelling issue)
* users might expect information to be found in another place (a categorization issue)
* the information they want is not accessible through a menu

It can be a UI issue:
* the positioning of the menu, size of the text, or color of the links doesn't highlight the desired parts of the site
* the navigation system is not very discoverable (e.g. a site does not use dropdown menus but instead forces users to click on a category name before showing sub-categories)

It can be another issue altogether:
* the category that you believe is important is irrelevent to a large number of your visitors

How do you determine if it's an IA issue?  Tree testing!

## Using Tree Testing To Determine If Your Info Architecture Is The Issue ##

There are two things you need to perform a tree test: a tree, and a set of tasks.

### The Tree ###

The tree is a text-only version of your site/information heirarchy.  You can create this in a spreadsheet and then transfer it into whatever software you use for administering the tree test.

<figure class="figure">
  <img src="{{ site.baseurl }}/images/NHL-Tree.png" class="img-responsive" alt="Partial NHL.com site tree" />
  <figcaption class="figure-caption">NHL.com site tree, partial</figcaption>
</figure>

The tree should all of your categories, both your top-level and sub-categories.  If you leave any part of your tree out, you run the risk of your test not being representative of users behaviors on your site. For example, if you leave out one part of your tree to test another and users perform well on your tree test, you might think that your tree is well structured. However, in reality, users often confuse one of your tested categories with one that you left out.

### The Tasks ###

The tasks you ask the users to find some information or complete some action using your tree. These should be informed by key business or website goals, like finding particular products, or donating to a charity. Each task has a "correct" answer, i.e., a category that is where the information should be found.

It's important to take the time to write good tasks. In general, tasks:
* should be specific
* should not give away the answer in the task (don't include the category name in the task)
* should not be too long (people may not see important details)

## Running the test ##

Tree tests are often run as unmoderated, remote sessions. This is a major benefit from a time and cost perspective, but it doesn't capture the full context of the user experience. For this reason, you should run a few tree tests in person before sending out a link to the test.

### Run a few in person ###

Running tests in person allows you to:
* identify any issues with your task wording
* get feedback from users on WHY they didn't choose certain categories, or why they chose others

It can be very to assess certain issues, like labelling issues, with quantitative data. If participants do not understand a particular label, or perceive it to be vague, they may not click on it (very often). The data will show you that people are not clicking on a category, but it will not tell you why. Asking users during in-person sessions can help identify what the issues are, and you can implement solutions before collecting the majority of your data.

### Run the rest remotely ###

After you're confident in your test, you can submit it to

### Things to keep in mind ###

When running a tree test, it's important to think about how running multiple tasks with the same user affects the results. The first time a user attempts a task, they have never seen the tree before, so they haven't learned anything about the tree (they have no learning bias). On subsequent tasks, participants have been exposed to the tree, and may recall some of the tree from previous traversals.  This can affect what routes they take, and how quickly and accurately they are able to complete tasks.  For this reason, you should try and minimize the number of tasks for each participant. You can also try to assign tasks that use different parts of the tree to minimize the learning bias.

## Tree Testing Results ##

After completing a tree test, you'll know the following for each task:
* *Direct Success Rate*: the percentage of participants that successfully completed the task without having to go up and down the tree
* *Indirect Success Rate*: the percentage of participants that successfully completed the task, but had to go up and down the tree to find it
* *Failure Rate*: the percentage of participants that did not successfully complete the task
* *Pathing*: the routes that people took up and down the tree before selecting an answer
* *Time to complete*: the amount of time taken to finish the task

Note: the names of the metrics may vary depending on the software you use.

## Summary ##

If people are able to find desired information easily and quickly during a tree test, but they are not able to find it on your site, it is likely a UI issue.  However, if people are having difficulty finding the desired information easily in a tree test, it is likely that you either have an IA problem (poorly labelled categories, or information categorized in unexpected ways).
