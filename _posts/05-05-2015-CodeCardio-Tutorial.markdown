---
layout: post
title:  "CodeCardio Tutorial"
date:   2015-05-05 09:51:25
categories: javascript tutorial codecardio
tags: featured
image: /assets/article_images/env-variables/env.png
---

# CodeCardio-Tutorial

In this tutorial, I'm going to talk about the basics of using [CodeCardio](codecard.io). CodeCardio was created by [DevMountain](devmounta.in) staff for use with our [Web-Dev bootcamp](https://devmounta.in/web-immersive).

The purpose of CodeCardio is to enable users to strengthen their coding skills.  CodeCardio has a number of JavaScript challenges, built to help you learn the fundamentals of JavaScript.  The site uses a testing system to ensure that you aren't only writing out the code, but you're also arriving at the correct answer.

## Step 1: Register

CodeCardio has three options for registration/authentication: 1) Local (using a username/email/password combination), 2) Facebook oAuth, and 3) Github oAuth.  

![Authentication]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_010_zpskei6nl60.png)

If you're not familiar with oAuth, it's an open standard for authentication, used across many services.  What that means is, you don't have to take the time to sign in/register with tons of sites.  Instead, you can use one of your current accounts to register/authenticate on many sites.

If you are planning on attending DevMountain, I highly recomment creating a Github account at this point and using it to authenticate for CodeCardio.  After doing this, logging in will be as simple as clicking the little button the right.

## Step 2: Finding Challenges

CodeCardio has challenges and sequences, which are collections of challenges.  You can view any challenge or sequence on the site from the [dashboard](https://codecard.io/a/dashboard).

Clicking on a sequence will bring you to a page where you can view all of the challenges in that sequence. You can access a challenge's page by clicking on the challenge name.

To demonstrate, I have created a sequence with three challenges. This is what my dashboard now looks like:

![dashboard]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_011_zpsxg2busuz.png)

One the left you can see my new sequence, 'These Questions, Three'.  If I click on the sequence, I will see all of the challenges in the sequence.

![sequence view]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_012_zpshqp0zecs.png)

I have three challenges in my sequence.  Let's start solving them!


## Step 3: Solving Challenges

Each challenge will have a title and description on the left side of the screen.  Instructions to solve the challenge will be in the description and/or the code itself.  Here's what it looks like:

![challenge view]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_013_zpsmleflsqx.png)

Follow the instructions and put your solution in the area on the right.  If you are successful, a confirmation messaage will appear, and you can move on to the next challenge by clicking 'next'.

![successful challenge]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/Tooltip_015_zpsncq54t0x.png)

There are a couple of ways your code might be tested.  The first is by checking the value of a variable, as we saw in the last example.  Another is testing the output of a function.  For example:

![test function]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_017_zpsdluygpau.png)

In this example, they are asking for a function called `quest`.  `quest` is supposed to return a string defining what your purpose is.  When you type submit, the test will invoke `quest()` and see what is returned.  If you've returned the right thing, you will pass.


Sometimes, you might struggle with a challenge and get it wrong a few times before you get it right. You might get different messages depending on what was wrong with your code.

![undefined]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_018_zpsvhoiapnr.png)

I get the above error if `colour` is undefined.

![wrong value]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/CodeCardio%20-%20Google%20Chrome_022_zpsasw2swvn.png)

And I get this error if `colour` is the wrong value.

The error messages will be different for most challenges.  Sometimes they will give you a hint or a direction to go to see why your code doesn't work.

If you want to show off how you did on challenges (or, if you want to send in your coding challenge to DevMountain), go to your profile,

![profile link]
(http://i1383.photobucket.com/albums/ah307/JIsraelTurner/Tooltip_021_zpsccchxidg.png)

copy the URL, and share away!
