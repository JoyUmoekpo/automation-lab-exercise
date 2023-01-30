# Automation Lab
In this lab you'll be writing automation tests to search Google and to test the functionality of the Movie List app.

## Part 1
Your goal in this section is to search for 2 movies and 1 TV show on Google

- Get started by dowloading the content for this lab from Frodo. Open the folder in VS Code.

- In the terminal cd into the google folder

- Run **_npm i_**

- There will be lots of errors with the file **_google.test.js_** that you’ll need to fix

- Follow along with the comments in the test file!

- In order to run your tests, you’ll type npm run test

## Part 2
- In your terminal, cd into the movieList folder, this page should look familiar!

- Run **_npm i_**

- You’ll need to make and write your test file from scratch

- Don’t forget your imports from **_selenium_**, the **_chromedriver_**, and **_driver_**

- Open the HTML file with liveserver (install it in the extensions tab of VS Code if you don’t have it already)

- **The URL you’ll go to will be the one from Live Server**
  - it’ll look like this: http://localhost:5500/exercises/automation/movieList/index.html

  - it might have 127.0.0.1 in the URL, which is the same as localhost, so you can replace the IP so it looks like the one above

- Write a **_beforeAll_** that connects to that URL

- Write an **_afterAll_** that quits the driver

- Write _at least_ 3 tests for the functionality of the Movie List app - these cannot be the same as the functions we covered in the demo. You could test crossing off a movie, deleting a movie, or even the notifications that are displayed.

When you are done, add, commit, and push your code to GitHub.
