# java-getting-started

A barebones Java app, which can easily be deployed to Heroku.  

This application support the Salesforce Elevate [Heroku workshop](http://agileforce.co.uk/heroku-workshop). 

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

## Running Locally

If you want to run this application locally, you will need to have Java JDK and Maven build tool installed.  You can also use the Foreman command from the [Heroku Toolbelt](https://toolbelt.heroku.com/) to run this application as it would run on Heroku.

```sh
$ git clone https://github.com/heroku/java-getting-started.git
$ cd java-getting-started
$ mvn install
$ foreman start web
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Documentation

For more information about using Java on Heroku, see these Dev Center articles:

- [Java on Heroku](https://devcenter.heroku.com/categories/java)
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
