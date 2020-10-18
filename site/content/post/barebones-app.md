---
title: Barebones app
date: 2011-12-05T22:03:00.000Z
description: >-
  In Eclipse, using the Google App Engine Tools v2.4 beta (ms1), and following
  the example in the demo video, I've created an "App Engine Connection Android
  Project" called "TubeMessage".


  This has created two linked projects in Eclipse:


  * TubeMessage-Android

  * TubeMessage-AppEngine
---
In Eclipse, using the Google App Engine Tools v2.4 beta (ms1), and following the example in the demo video, I've created an "App Engine Connection Android Project" called "TubeMessage".

This has created two linked projects in Eclipse:

* TubeMessage-Android
* TubeMessage-AppEngine

Out of the box this functions as a simple messaging app, so it seem like a lot of the work has already been done for me!

While setting up this project I also registered the app for C2DM access - this is needed in order to use C2DM to associate the app with Google accounts.

My first deviation from the demo video has been that I wasn't able to log into a google account from the Android emulator - I fixed this as per this [StackOverflow answer](http://stackoverflow.com/questions/3260868/android-emulator-trouble-creating-user-accounts) - First install the Google APIs (API8, since my real phone runs Android 2.2) via the Android SDK and AVG Manager, and then created a new virtual device with Google APIs as the target, and also changed the TubeMessage-Android's target (Properties -> Android) to be "Google APIs".