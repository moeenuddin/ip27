---
layout: post
title:  Phantomjs signup and search code
date:   2017-11-11 02:48:43 +0500
categories: Code igniter Phantomjs Profile Work
---

Hi, I came across Phantomjs. Excellent thing. I just got so much excited that I wrote a script.
It tries to go to a site, open a page, with username and password. and tries to do various action
on users behalf.

Office Automation can be achieved via this tool. Other tools like selenium, I will try them.

Drop your comments to my email address or twitter account.

I used to open a page, do a set of action, navigate, and close. This was pretty simple.

See <a href="Phantomjs.org">Phantomjs.org</a>

	// Simple Javascript example

	console.log('Loading a web page');
	var page = require('webpage').create();
	var url = 'http://phantomjs.org/';
	page.open(url, function (status) {
	  //Page is loaded!
	  phantom.exit();
	});

