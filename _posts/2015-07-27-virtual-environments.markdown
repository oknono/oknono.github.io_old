---
layout: post
title:  "Flask and Virtual Environments"
date:   2015-07-27 09:36:00
categories: python flask
---

Most of last week I spend playing around with [Flask](http://flask.pocoo.org/).The whole MVC model is starting to make more sense to me. My personal page is currently built in Flask,
and a project I did that using the wikipedia API to check if Dick Cheney is dead ([Personal Page](http://www.oknono.net) and [Is Dick dead?](http://www.isdickdeadyet.xyz)). Both are deployed using [Heroku](https://www.heroku.com/), which is surprisingly easy to use. I made a small presentation about how I built the Dick Cheney webpage. You can [get the PDF here]({{ site.url }}/assets/Thursday_Presentation.pdf).

Working with Flask also taught me a lot about working with virtual environments. I had some trouble with getting virtualenvwrapper to work, but currently it seems to work fine. Basically a virtual environment means that you can install modules for just this environment. This makes sure that dependencies don't influence each other, and that you can work on different projects using different dependencies (for instance a project using Python 2.7 and a project using Python 3). More on [Virtual Environments](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
