# Ruby on Rails Tutorial sample application

This is basically a complete, and more importantly generic, Ruby on Rails web app. It supports user signup, login, logout, account activation, password reset, and third party email sending. In other words, everything you need to build a Rails web app.

There might be a few mentions of "microposts" throughout this app, but they shouldn't reference anything. Overall, you can build a good Rails web app off of everything included in this release. This is ideal for hackathons where you need to get the core part of the web app up and running as quickly as possible.

This release assumes that you'll be using Heroku, but you can also run it locally with no issues. You just won't get any email-sending capabilities. This is the resulting sample application (sans microposts functionality) of [Michael Hartl's](http://www.michaelhartl.com/) [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/).

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```