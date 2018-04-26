---
title: Network IP Map Page Details
keywords: network
summary: "An overview of how the network IP Address page is built."
sidebar: main_sidebar
permalink: network-ip-map-details.html
folder: network
category: network
date: 2018-02-03 19:52:53 -0700
toc: false
---

There are quite a few moving pieces involved in the creation of the Network IP Map.  The core information is stored in a shared Google Sheet spreadsheet that's unique to a specific Google user account.  Javascript is used in conjunction with the proper access token to:

- Read the corresponding Google spreadsheet.
- Write the contents of that sheet to `network.yaml` which is found in the `_data` folder.

The Javascript is contained in the file `index.html` in the `pull-sheet` folder at the root of this site.  There's a URL commented in that page that shows you the variables that need to be provided.  When the URL in that file is given the correct parameters and is called from a browser or command prompt, it passes the variables to the Javascript and the Spreadsheet is accessed and all of the resulting data is written to the `network.yaml` file.

The URL that's called is currently running on a cron job that fires off every 5 minutes to ensure that the data saved to the spreadsheet is no older than 5 minutes old.  If there are no changes in the data, the `network.yaml` file remains untouched.

The actual page where you view the information, which is called `network-ip-map.md`, is published in the `pages/network` folder.  That page pulls a page from `_includes` called `network_ip_map.html` which contains a `for loop` that reads the `network.yaml` file in the `_data` folder and populates the table with the correct information provided by the initial Javascript.

When all is said and done, any data that is provided to the spreadsheet will be shown in the table.

{% include links.html %}
