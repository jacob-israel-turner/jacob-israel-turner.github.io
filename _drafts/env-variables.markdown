---
layout: post
title:  "Environment Variables"
date:   2015-04-29 21:15:25
categories: unix windows node
tags: featured
image: /assets/article_images/env-variables/env.png
---
# Understanding Environment Variables

The purpose of this tutorial is to help you understand environment variables, how they work with your system, and how they can make your life easier when working with [NodeJS](https://nodejs.org/).

## Your Computer's Environment

Environment variables, on the most basic level, describe details about your system. Programs installed on your system will use environment variables in order to navigate their way around your computer.  For example, if a program needs to place data in a folder for a specific user, it might use the HOME variable to know where to put it. If the program wanted to put something in a user's downloads folder, it might use the HOME variable and construct a path like so:

![](/assets/article_images/env-variables/home-example.png 'Home env example')
