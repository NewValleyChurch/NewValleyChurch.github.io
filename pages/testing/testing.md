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

The menu on the left is built by using an HTML file called Sidebar2.html in the `_includes` folder which loops through all of the pages in the site.  The side bar loops first to locate category names based upon the front matter in the page, and then again to list each page that is set to that category.

The front matter in _this_ page has the category to "sound", the folder to "testing", and the layout to page2.

`sidebar: none` disables the default theme sidebar to make room for the custom auto-build menu.

## Current Problem

I'm stuck getting the navgoco jquery menu to generate indices for each category, so you'll notice that the first category has an accordion effect, and the 2nd and 3rd do not.
