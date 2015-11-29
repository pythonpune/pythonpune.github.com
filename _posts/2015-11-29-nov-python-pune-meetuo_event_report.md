---
layout: entry
title: November Python Pune Meetup 2015
category: meeting-notes
---

[November Python Pune meetup 2015](http://www.meetup.com/PythonPune/events/226879086/) was organized at [Red Hat, Pune (India)](http://www.redhat.com/en) on 29th Nov, 2015.

The theme of this month meetup was "Test, Build and Deploy your python projects".

The meetup started with the first workshop "Package your python code using setuptools and wheels", where [Chandan Kumar](https://twitter.com/ciypro) talked about:

* Why to package your python code?
* Tools required for packaging
* Necessary files like setup.py, setup.cfg, LICENSE and MANIFEST.in file needs to be included in the project repo.
* How to define package metadata and configuration with in setup.py and setup.cfg files
* Explained about setuptools and wheels format
* Difference between eggs and wheels format
* How to create source distribution and binary wheels distribution
* How to ship binary files with wheels.
* Talked about version-bump and check-manifest tools while creating packages

For more information, check [python packaging website](https://packaging.python.org/en/latest/).

The second workshop "Python testing using Mock and PyTest" was given by [Suraj Deshmukh](https://twitter.com/surajssd009005).

He covered:

* Introduction to python unittest mock library
* followed by examples to
 * to mock values with in a test
 * How to customize mock objects
 * How to use specs to define attributes and create specs automatically
 * Covered how to patch methods using mock through an script to upload texts on fpaste.org
 * How to use side_effects through mock with in a method
 * Introduction to PyTest
 * Difference between Mock and PyTest
 * How to write and run PyTest
 * How to use fixtures with in a test.

Here is the Slide link for ["Python testing using Mock and PyTest"](https://docs.google.com/presentation/d/19-gmffTji8diJfTL3-8NvgtXLskZOVhkSRU6Ng-v7no/edit?pli=1#slide=id.gd5ba8fb7c_0_46)

Then we have a long discussion between the attendees on different topics by sharing their problems and field of expertise.

And, the last workshop "Deploying a flask application on OpenShift" was taken by [Abhijeet Kasurde](https://twitter.com/Pyro46).

He had given a hands-on workshop on:

* Create an account on OpenShift
* Internals of OpenShift, gears and cartridges
* How to install and use rhc to deploy your sample application
* Clone a repo from OpenShift project repo created domain using git
* Creating a simple flask app and displayed welcome message on OpenShift deployed app main page.
* How to update your flask app on OpenShift Instance and integrate Jenkins on each commit.

Here is the slide link for ["Deploying a flask application on OpenShift"](http://www.slideshare.net/godfatherabhi/deploying-flask-web-app-using-openshift)

Thanks to Red Hat, Speakers and Volunteers for making the event successful.
