---
title: "First Android App: Messaging with Offline support"
date: 2011-12-05T20:25:00.000Z
description: "So, I'm teaching myself how to write Android apps. I've got Hello
  World under my belt, and for my first proper app I'm going to scratch an itch:
  offine support for online apps."
---
So, I'm teaching myself how to write Android apps. I've got [Hello World](http://developer.android.com/resources/tutorials/hello-world.html) under my belt, and for my first proper app I'm going to scratch an itch: offine support for online apps.

I play various games on my Android phone as I commute to work on the London Underground ([WordFeud](https://market.android.com/details?id=com.hbwares.wordfeud.free) is a current favourite). Naturally, for a large portion of this journey I don't have network access, and I've wondered why there don't seem to be any games that allow you to make moves while offline and transmit them automatically when online. Is there a technical reason why this is particularly difficult? It's obviously not impossible, since both the built-in Mail client and the GMail app support this.

Inspired by this [talk from Google IO](https://youtu.be/M7SxNNC429U), I'm going to implement a simple messaging app using Google App Engine, and then add off-line support for it.