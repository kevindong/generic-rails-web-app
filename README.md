# Generic Rails Web App

This is basically a complete, and more importantly generic, Ruby on Rails web app. It supports user signup, login, logout, account activation, password reset, and third party email sending. In other words, everything you need to build a Rails web app.

There might be a few mentions of "microposts" throughout this app, but they shouldn't reference anything meaningful. Overall, you can build a good Rails web app off of everything included in this release. This is ideal for hackathons where you need to get the core part of the web app up and running as quickly as possible.

This release assumes that you'll be using Heroku, but you can also run it locally with no issues. You just won't get any email-sending capabilities. 

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

## License

My original work (essentially a tiny bit of the initial commit and everything after that) are licensed under the MIT License.

The original framework of this web app was based on [Michael Hartl's](http://www.michaelhartl.com/) [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/), which itself is [jointly licensed under the MIT License and the Beerware License](https://www.railstutorial.org/book/frontmatter#copyright_and_license).