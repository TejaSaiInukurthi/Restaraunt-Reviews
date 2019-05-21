# Mobile Web Specialist Certification Course

* * *

#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1.  In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    -   In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
    -   Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.

2.  With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3.  Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4.  Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

# Restaurant Reviews

The goal of this poject is to
	1. Make the web application Responsive.
  2. Make this application Offline first by using serviceWorker and to add a manifest file to add icon to application.
	2. Have to increase the accessibility in HTML and CSS along with javascript.

## Running the Application

+ Cloned the repository which was provided by udacity to my personal computer by using `git clone` command.
+ Make sure you have already installed  python 3 in your system.
+ Run the python http server by using `python -m SimpleHTTPServer` command it took `8000` as port.
+ Finally opened `localhost:8000` url in my browser to check the output.


## responsive design:

1.  For bringing responsiveness we need to add a meta tag in html pages along with that we need to  
    add meta description tag.
2.  After adding those tags we need to add media queries in the stylesheet
3.  for mobile view that ranges from 320px to 480px.
4.  for ipad view that ranges from  480px to 767px.
5.  for responsive view that ranges from 768px to 1024px.

## storing caches:

1.  We need to add `service_worker.js` to store the caches in browser to make application run offline also.
2.  we need to add `manifest.json` file for generating icon to our page. Also add icon images to image folder.

## checking Accessibility:

1. we need to check the accessibility of our application by running audits and make sure to get accessibility to its maximum.

## Conclusion:

Hence I conclude this project is very helpful in making a responsive design for a website and how to add the icon to our website and how to make use of service worker for our website to make it work even offline.
