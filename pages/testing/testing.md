---
title: Testing Automatic Sidebar
layout: page2
category: sound
keywords: QU-32, mixer, wireless mic
summary: "Implementing a loop that auto builds the menu on the left."
permalink: testing.html
folder: testing
sidebar: none
toc: false
---

## The Menu

The menu on the left is built by using an HTML file called Sidebar2.html in the `_includes` folder.  The front matter in this page sets the category to "sound", the folder to "testing", and the layout to page2.

`sidebar: none` disables the default theme sidebar to make room for the custom autobuild menu.

## Current Problem

I'm stuck getting the navgoco jquery menu to generate indices for each category, so you'll notice that the first category has an accordion effect, and the 2nd and 3rd do not.
