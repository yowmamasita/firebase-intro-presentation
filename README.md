# Intro to Firebase

This slide deck can be customized to give an introductory talk about Firebase. It is powered by [reveal.js](http://lab.hakim.se/reveal-js), a wonderful and powerful framework for creating HTML presentations.

### [Boilerplate Site - https://intro-to-firebase.firebaseapp.com/](https://intro-to-firebase.firebaseapp.com/)

## Presentations

Here are some past presentations made with this desk:

| Presenter | Event | Date | Contact |
| --------- | ----- | ---- | ------- |
| Mike Koss | [Seattle GDG](https://plus.sandbox.google.com/events/cp5b162fccbtrk4l3ah2blb5je8) | April 20, 2015 | koss@firebase.com |
| Jacob Wenger | GDG Leads Summit | May 27, 2015 | jacob@firebase.com |

If you end up using this deck, please let us know so we can share the presentation here!

## Setup

This repo uses npm and Grunt to install dependencies, build the deck, run tests, and run a local web
server for the content. To get started, run the following commands:

```bash
$ git clone git@github.com:firebase/firebase-intro-presentation.git
$ cd firebase-intro-presentation         # go to the firebase-intro directory
$ npm install -g grunt-cli               # globally install grunt task runner
$ npm install                            # install local npm build / test dependencies
$ bower install                          # uses bower for polymer dependency
```

To build the slide deck and run the test suite:

```bash
$ grunt --force
```

To open the slide deck using a local web server:

```bash
$ grunt serve
```

## Deploy

Ideally, you'll want to run this on a public website for viewers to see after the presentation. You can use [Firebase Hosting](https://www.firebase.com/docs/hosting/) to deploy this presentation for free!

You can then view the slide deck at [http://localhost:8000](http://localhost:8000).
