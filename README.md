Bustle Clone
============

by <a href="http://duanemoody.io" target="_blank">Duane M. Moody</a>.

Bustle is a news site written with Ember.js.  This project will rebuild some of the features of Bustle.

Epicodus Coursework Objectives
------------------------------

* To start, build a homepage with 4 sample headlines and photos hard-coded into the template and a nav bar on the top. For now, don't put any real links on the nav bar.
* Next, let users click on a headline or photo to view the full story. Keep the navbar showing.
* Now, on the Bustle homepage, notice that there is a "carousel" at the top, with arrows on either side; when you click an arrow, a new image moves to the center of the screen. Add this feature. Don't worry about the scrolling effect. Also don't worry about linking the images to anywhere.
* When a user hovers their mouse over the social buttons in the upper right corner of the Bustle homepage, a little menu appears. Implement this same functionality, but only when a user clicks on the icons. (If you'd like to try to get it working with hover, you'll need to do something like ```{{action "toggleSocialIcons" on="mouseEnter"}}```.)


Installation
------------

Install Bustle Clone by first cloning the repository.  
```
$ git clone http://github.com/dmmoody/bustle_clone.git
```

Running the app
---------------

To run the app, ```\cd``` into the root folder for the app and start the webserver:
```
$ python -m SimpleHTTPServer
```

In your web browser, go to http://localhost:8000

Contribute
----------

- Issue Tracker: https://github.com/dmmoody/bustle_clone/issues
- Source Code: https://github.com/dmmoody/bustle_clone

Support
-------

If you are having issues, please let me know at: dmmoody@gmail.com

Bug reports
===========

If you discover any bugs, feel free to create an issue on GitHub. Please add as much information as possible to help me fixing the possible bug. I also encourage you to help even more by forking and sending me a pull request.

https://github.com/dmmoody/bustle_clone/issues

License
=======

MIT License. Copyright 2014 Duane M. Moody | <a href="http://moodyco.de">MoodyCode</a>