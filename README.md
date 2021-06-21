# Node.js Masterclass Homework Assignment

This repository contains the homework assignment for [Node.js Master Class](https://pirple.thinkific.com/courses/the-nodejs-master-class) by [Pirple](https://www.pirple.com/) that is focused on building a RESTful API, web app GUI, and a CLI in plain Node JS (ES6 Javascript) with **no NPM or 3rd-party libraries**.

![nodejs](https://nodejs.org/static/images/logos/nodejs-new-pantone-white.ai | width=48)

## Homework Assignments

### Assignment #1: Backend

You are building the API for a **system monitor**.

Here's the spec from your project manager: 

**The Node JS Master Class - No Frameworks, No External Libraries, No NPM. 


# RESTful API, and web app, and a CLI in plain Node.js with no 3rd-party libraries.

The app is usable visite [Guetter.app](https://guetter.app)

1. The API listens on a PORT and accepts incoming HTTP requests for POST, GET, PUT, DELETE and HEAD
2. The API allows a client to connect then create a new user, then edit and delete that user
3. The API allows a user to "Sign in" which gives them a tokem that they can use for subsequent authenticated requests
4. The API allows the user to "Sign out" which invalidates their token
5. The API allows a signed in user to use their token to create a new "check"
6. The API allows a sigened in user to edit or delete any of their checks
7. In the background, workers perform all the "checks" at the appropiate times, and send alerts to the users when a check changes its state from "up" to "down", or vice versa
