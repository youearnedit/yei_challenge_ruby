# YouEarnedIt Ruby Code Challenge

Hello!  We're so thrilled you're applying to join us at YEI!

To help us learn a little about how you work and write code, we ask that you spend a few hours (3-5) on the following code problem. The goal of this is for you to have an opportunity to show your skills as a developer with Ruby and the Rails framework, and your committment to writing well crafted code, in a setting that is most comfortable to you.  Please don't spend too much time - we want to be mindful of what we're asking you to commit.  The goal of this is not to have a production-ready application.  This challenge is a sort of 'choose your own adventure' problem based around premise below.


### Our Challenge

  Using the public [Github API](https://developer.github.com/v3/) or Github's GraphQL API, build a rudimentary service in Ruby that queries the [Rails](https://github.com/rails/rails) repository for the latest open issues that are unassigned.  The service should provide the ability to filtered the results by component (explained below) and ordered by comment counts, as well as anything else your implementation needs.


### Rails Components

In the repository, the Rails team uses labels to define the components of the stack the issues relate to.  The components we'd like you to get issues for are:

- ActionCable
- ActionMailer
- ActionPack
- ActionView
- ActiveJob
- ActiveModel
- ActiveRecord
- ActiveStorage
- ActiveSupport
- Asset Pipeline

Feel free to ignore the other labels.

### Things you can/should use:
- Ruby (*required*)
- Rails/Sinatra/Grape/no web stack - you're welcome to build a ruby only app thats CLI based, or a web app.
- Javascript, JQuery, ES6, etc - if what you want to build needs it, please use it!
- Rspec, Minitest, Test::Unit, Bacon, Riot - write tests, use what you like.
- MongoDB, PostgreSQL, SQLite - if you need a database, please pick one of these.

### Things you should do:
- Show us your skills - this can be done by building out a robust api integration, or building an ETL processor to persist the data from the API, or build a nice clean API of your own to expose the data you transform from Github, or build a fancy UI around a basic API of your own using other tools like JS.  This is where you can _really_ show off who you are and what you can do.  Just don't go too overboard on time.
- Write clean, well tested, well organized code.
- Leave comments if appropriate, but don't worry about commenting up everything, just explain any 'hard parts'.

### Things to avoid doing:
- Don't use a gem for the github api, we want to see that you can solve for it.  If you're doing a GraphQL integration, feel free to use GraphQL libraries though
- Don't submit broken code - your solution should be functional
- Don't spend too much time
- Don't break out your code into separate application services.  A monolith is fine.
- Please don't put your solution on Github.  We'd love our candidates to keep their solutions to themselves.

### What we're looking for in a solution
We want to see that you can a) code, b) problem solve, c) organize your thoughts into a reasonable implementation.  We love looking at elegant solutions, but don't be too crafty or non-normal in your coding style.  We're looking to see that you follow common standards and conventions, and that you follow well understood paradigms like DRY, separation of concerns, and good object orientation.

At YEI, we test our code as often as we can to ensure things are sound - we'd expect the same out of you, so please have some test coverage around the important parts.  In the interest of time, you don't need 100% complete coverage, so feel free to ignore things like view tests and feature tests.  Unit tests of the important parts is more than enough. Although we use RSpec exclusively for our Ruby tests at YEI, you're welcome to use alternatives if that's faster for you.

### Preparing to submit
- Write a README - this should explain what you implemented (high level), how to get the code running, and how to interact with it (CLI, web app, etc.)
- Please include a .ruby-version file and a Gemfile for dependencies
- While we love git and github, we don't want our candidates to be able to see each other's work and the history of the project.  Please take your entire directory, and zip or tarball it for submission.
