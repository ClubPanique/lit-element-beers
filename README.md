# LitElement Beers - LitElement tutorial

I have built this [LitElement tutorial](https://github.com/LostInBrittany/lit-element-beers) as a quick entry point to [LitElement](https://lit-element.polymer-project.org/). 

For the last several years, I've taught a web-development module in an Engineering School with a rather restrictive network. As I plan to use this tutorial in next year module, in order to explain web components and LitElement to our students, I needed a tutorial that could be played without network access, i.e. without npm or webpack. So the whole tutorial needed to be doable even behind a very restrictive proxy, and all the dependencies are included inside the git project.

![Logo](/img/logo-500px.png)


## What are the objectives of this tutorial

Follow the tutorial to see how web components and LitElement make browsers smarter — without the use of native extensions or plug-ins:

+ See examples of how to use client-side data binding to build dynamic views of data that change immediately in response to user actions.
+ See how LitElement keeps your views in sync with your data without the need for DOM manipulation.
+ Learn how to build technical elements to make common web tasks, such as getting data into your app, easier.

When you finish the tutorial you will be able to:

+ Create a dynamic application that works in all modern browsers.
+ Create custom elements, with its looks and its behavior encapsulated inside, setting the bases of a true component architecture client-side
+ Use data binding to wire up your data model to your views
+ Get data from a server
+ Use a router to add multipage capabilities to your application

The tutorial guides you through the entire process of building a simple application. Experiments at the end of each step provide suggestions for you to learn more about LitElement and the application you are building.

You can go through the whole tutorial in a couple of hours or you may want to spend a pleasant day really digging into it. If you're looking for a shorter introduction to LitElement, check out the official website.

![Screenshot](./img/lit-element-beers-final.jpg)  

![Screenshot](./img/lit-element-beers-final-details.jpg)


## What do I need to use this tutorial?

The tools strictly needed for this tutorial are a modern web browser (ideally [Chrome](https://www.google.com/chrome/) or [Chromium](https://www.chromium.org/)), a text editor (we suggest the excellent [Visual Studio Code](https://code.visualstudio.com/) or [Atom](https://atom.io))), [Node JS](https://nodejs.org), and a web-server to test your code.

If you have Python in your system, the easiest way would be to run the embeded SimpleHTTPServer. Go to the project directory and run

```
# Python 2.x
python -m SimpleHTTPServer
```

or 

```
# Python 3.x
python -m http.server
```

to start the web server. Now, open a browser window for the app and navigate to http://localhost:8000/app/index.html to see the current state of the app.

If not, you can use [NodeJS](http://nodejs.org). We have put a minimalist JavaScript web-server on `./scripts/web-server.js`. To see the app running in a browser, open a separate terminal/command line tab or window, go to the project directory and then run `node ./scripts/web-server.js` to start the web server. 


## How is the tutorial organized 

As the computer used for the course haven't Git, we have structured the project to allow a Git-less use. The `app` directory is the main directory of the project, the working version of the code. The tutorial is divided in steps, each one in its own directory:

1. [Static HTML](./step-01/)
1. [Using LitElement elements](./step-02/)
1. [Creating a new element](./step-03/)
1. [Filtering](./step-04/)
1. [Sorting](./step-05/)
1. [Calling the server](./step-06/)
1. [Routing URLs using App Router](./step-07/)

In each step directory you have a README file that explain the objective of the step, that you will do in the working directory `app`. If you have problems or if you get lost, you also have the solution of each step in the step directories. So if you want to see the intended result of  the 6th step, you can point your browser to http://localhost:8000/step-06/index.html


## What should I do now?  

OK, now you're ready to follow this tutorial. If you're familiar with git, begin by cloning this repository (`git clone https://github.com/LostInBrittany/lit-element-beers`), else you can simply download the zipped file from [GitHub](https://github.com/LostInBrittany/lit-element-beers/archive/master.zip).

Now can go to [step-01](./step-01) and begin to follow the README of that step. Let's begin!