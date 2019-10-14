# Project

Autocomplete website/widget

### Description

A website that enables users to quickly find and select words from a list of suggestions, as they type.
The list is dynamically generated from a dictionary, the dictionary needs to be requested through an API request **from the backend**.
A large data file is required to search through - consider the best data structure for this (e.g. .txt or .json).
Consider how implementation affects user experience and web performance (e.g. time to load and search through the data file).
Task
Your task is to build a site which will update as you type (an autocompleter), as per the description above.

Goals
We expect back-end testing using tape (test as many components as you can) and basic front-end testing. Please note that we expect tests on pure functions and not on the router or the DOM.

Host your project on heroku, see resource.

Use module.exports and require to break a single large server file into smaller modules.

Consider what would be a good server file structure based on what we have discussed over the week


### Goals:
1) Use an API to import your dictionary

2) Make your API calls from the back-end using the Request module (or one you build yourself)

3) Filter your dictionary acording to the user's input

4) Display the results of the autocomplete to the user

5) Your server should contain a minimum of 2 routes

6) We expect to see lots of tests! Modularise your code and test all your pure functions. Write tests for as much of your back-end and front-end logic as you can. We don't expect tests on the DOM.

7) Test your server routes by injecting fake HTTP requests using Supertest (including testing for 404's). _Note - you are not required to test any server route that makes an API call, as this will make the test impure (a test that depends on an external factor is not reliable)_

8) Host your project on Heroku, see [resources](https://github.com/foundersandcoders/master-reference/blob/master/coursebook/week-5/resources.md)

9) Use module.exports and require to break a single large server file into smaller modules.

10) Consider a good server file structure based on what we have discussed over the week.

11) Employ continuous integration on your project with Travis or a similar tool. (If you decide to use Travis, we strongly recommend that you host this project in your own repo rather than in your cohort's FAC repository to avoid all builds getting queued together)

12) Use CodeCov or a similar tool to report and track test coverage.

13) Include Error Handling. For example:
  - if a user attempts to make a request to a non-existent route to your server (404 - as mentioned above), provide the user with a custom response.    
  - if there is a [programmer error](https://github.com/foundersandcoders/error-handling-workshop#kinds-of-errors) on your server (e.g. a handler function does not act as intended), provide the user with a custom response (500 status code).

14) Include a user input field on your web app and include server-side validation to protect your server from potentially malicious user input.

15) Display continuous integration and code coverage badges on your project README. 

### Stretch goal 😊:

16) Create a route and functionality for a POST request.

**Most importantly!**
Have Fun! :heart:
