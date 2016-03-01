Loca
====

[![Build Status](https://travis-ci.org/camelaissani/loca.svg?branch=master)](https://travis-ci.org/camelaissani/loca)

[![Coverage Status](https://coveralls.io/repos/github/camelaissani/loca/badge.svg?branch=master)](https://coveralls.io/github/camelaissani/loca?branch=master)
<sup>Only backend code is covered see issues [#8](https://github.com/camelaissani/loca/issues/8) and [#9](https://github.com/camelaissani/loca/issues/9)</sup>

## What's Loca?

This nodejs project is a tentative of web application that offers a toolkit for owners of buildings, flats, offices, meeting rooms, car parks, letter boxes...

The idea is to make easy the management of properties and occupants by proposing many services:
 - Gather all information of your properties and occupants in one place
 - Create rent contract from templates available in the system
 - Follow the rent payments month by month
 - Template letters for recovery of not paid rents

![Loca](http://www.nuageprive.fr/images/loca-sample.png "Open source real estate management")

[Check out the live demo.](http://demo.nuageprive.fr/)

## Getting started
First of all, you must have **nodejs** and **mongodb** installed on your computer.

Run these commands in your terminal in the directory of the cloned repository.

```
npm install
node server.js
```

For developers, open a first terminal in the project directory a run these commands:

```
npm install
npm run dev
```

Open a second terminal in the same directory and run:
```
npm run watch
```
It will automatically build when the source code changes.

Sorry guys but currently the application is in french...

Why I created this application?
-------------------------------
Simply to help my best friend and I to manage properties that we rent.

Above all, to have a good reason to play with node and javascript :-)

