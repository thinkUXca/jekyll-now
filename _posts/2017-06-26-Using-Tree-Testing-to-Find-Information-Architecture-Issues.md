---
layout: post
title: Using Tree Testing to Find Information Architecture Issues
author: jonathan
tags: [information architecture, tree testing]
---

Understanding why users aren't using certain parts of your site can be a daunting task if you don't have the right tools. Tree testing is a great way to assess your site's information architecture and discover problems with your labels and categorization.

## What is Tree Testing? ##

Tree testing is a technique that helps to test if your information architecture (IA) matches the mental models of your users. It aims to answer the following questions:
* Can people easily find information on your website?
* Do your menu/category names make sense to your users?
* Is information categorized in a way that users expect?

Tree testing is an important IA technique because it _separates the user interface from the information structure._ During a tree test, users do not interact with the user interface, they navigate using only links. By separating out the structure from the interface, you can determine if an issue is caused by the information architecture (e.g. people don't understand your category names, your hierarchy doesn't match how users think about the information, etc.) or by the navigational components and UI layout. Let's look one of the most common issues clients have with their websites.

## People Aren't Visiting An Important Part Of My Site! ##

Users failing to reach a key section of your website can be caused by faulty information architecture, UI design, or both. Figuring out which is very important: if you "guess" and guess wrong, it can be very costly in terms of both time and money. For example, if your client thinks that users aren't visiting a page enough due to the navigation not highlighting it enough, they may ask their developers to redesign the site in a way that puts more focus on it (through placement, colour, perhaps a new navigation system, etc.). This can have numerous unintended consequences, such as reducing traffic to parts of the site that were already performing well, and it may not solve the issue. This kind of knee-jerk reaction based on gut feelings can be very expensive and leave you in the same situation you started in.

Reasons the problem could be due to an IA issue:
* Users might not understand the category names you've chosen, so they never navigate to the desired categories (a labelling issue)
* Users might expect information to be found in another place (a categorization issue)
* The information they want is not accessible through a menu

Reasons the problem could be due to a UI issue:
* The positioning of the menu, size of the text, or colour of the links doesn't highlight the desired parts of the site
* The navigation system is not very discoverable (e.g. a site does not use dropdown menus and instead forces users to click on a category name before showing sub-categories)

It could also be another issue altogether, such as if the category that you believe is important is actually irrelevant to a large number of your visitors.

How do you determine if your problem is an IA issue? Tree testing!

## How Tree Testing Works ##

There are two things you need to perform a tree test: a tree, and a set of tasks.

### The Tree ###

The tree is a text-only version of your site/information hierarchy. You can create this in a spreadsheet and then transfer it into whatever software you use for administering the tree test.

<figure class="figure">
  <img src="{{ site.baseurl }}/images/NHL-Tree.png" class="img-responsive" alt="Partial NHL.com site tree" />
  <figcaption class="figure-caption">NHL.com site tree, partial</figcaption>
</figure>

The tree should include all of your categories, including both top-level and sub-categories. If you leave any part of your tree out, you run the risk of your test not being representative of actual user behaviour on your site. For example, if you leave out one part of your tree to test another and users perform well on your tree test, you might think that your tree is well structured. However, your users may confuse one of your tested categories with one that you left out.

### The Tasks ###

Once you have the tree, you're going to ask users to find some information or complete some action using the tree. These tasks should be informed by key business or website goals, such as finding particular products, or donating to a charity. Each task has a "correct" answer, i.e., a category that is where the information should be found.

It's important to take the time to write good tasks. In general, tasks:
* should be specific
* should not give away the answer in the task (e.g. don't include the category name in the task)
* should not be too long (people may not see important details)

## Running the test ##

Tree tests are often run as unmoderated, remote sessions. This is a major benefit from a time and cost perspective, but it doesn't capture the full context of the user experience. For this reason, you should run a few tree tests in person before sending out a link to the test.

### Run a few in person ###

Running tests in person allows you to:
* identify any issues with your task wording
* get feedback from users on *why* they didn't choose certain categories, or why they chose others

It can be very helpful to use quantitative data to assess certain issues, such as labelling. If participants do not understand a particular label, or perceive it to be vague, they may not click on it very often. Quantitative data will show you that people are not clicking on a category, but it will not tell you why. Asking users during in-person sessions can help identify what the issues are, and you can implement solutions before collecting the majority of your data.

### Run the rest remotely ###

After you're confident in your test, you can run the remainder of your tests using a remote testing tool. This will reduce the time required to both administer and analyze results from the test.

### Things to keep in mind ###

When running a tree test, it's important to think about how running multiple tasks with the same user affects the results. The first time a user attempts a task, they have never seen the tree before, so they haven't learned anything about the tree (they have no learning bias). On subsequent tasks, participants have been exposed to the tree, and may recall some of the tree from previous traversals. This can affect what routes they take, and how quickly and accurately they are able to complete tasks. For this reason, you should try and minimize the number of tasks for each participant. You can also try to assign tasks that use different parts of the tree to minimize the learning bias.

## Tree Testing Results ##

After completing a tree test, you'll have learned the following for each task:
* *Direct Success Rate*: the percentage of participants that successfully completed the task without having to go up and down the tree
* *Indirect Success Rate*: the percentage of participants that successfully completed the task, but had to go up and down the tree to find it
* *Failure Rate*: the percentage of participants that did not successfully complete the task
* *Pathing*: the routes that people took up and down the tree before selecting an answer
* *Time to complete*: the amount of time taken to finish the task

Note: the names of these metrics may vary depending on the software you use.

## Summary ##

If people are able to find desired information easily and quickly during a tree test, but they are not able to find it on your site, it is likely a UI issue. However, if people are having difficulty finding the desired information easily in a tree test, there's a good chance that you have a problem with your information architecture.
