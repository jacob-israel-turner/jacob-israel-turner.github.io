---
layout: post
title:  "Environment Variables"
date:   2015-04-29 21:15:25
categories: unix windows node
tags: featured
image: /assets/article_images/env-variables/env.png
---
# Understanding Environment Variables

The purpose of this post is to help you understand environment variables, how they work with your system, and how they can make your life easier when working with [NodeJS](https://nodejs.org/).

## Your Computer's Environment

Environment variables, on a basic level, describe details about your system. Programs installed on your system will use environment variables in order to navigate their way around your computer.  For example, if a program needs to place data in a folder for a specific user, it might use the HOME variable to know where to go. If the program wanted to put something in a user's downloads folder, it might use the HOME variable and construct a path like so:

![](/assets/article_images/env-variables/home-example.png 'Home env example')

Most installation processes use environment variables intelligently, in order to install in the correct directories and use your system as intended.

In order for a program to be executed from the command line, it must be listed in the **PATH** environment variable.

> PATH is an environment variable(...) specifying a set of directories where executable programs are located. In general, each executing process or user session has its own PATH setting.

> \- [Wikipedia: PATH(variable)](http://en.wikipedia.org/wiki/PATH_%28variable%29)


