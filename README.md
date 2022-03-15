# borealis-pg-demo-app

A simple Java app for Heroku that demonstrates the [Borealis Isolated Postgres](https://elements.heroku.com/addons/borealis-pg) add-on.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/OldSneerJaw/borealis-pg-demo-app)

## Running Locally

Make sure you have Java and Maven installed.  Also, install the [Heroku CLI](https://cli.heroku.com/).

```sh
$ git clone https://github.com/heroku/java-getting-started.git
$ cd java-getting-started
$ mvn install
$ heroku local:start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

If you're going to use a database, ensure you have a local `.env` file that reads something like this:

```
JDBC_DATABASE_URL=jdbc:postgresql://localhost:5432/java_database_name
```

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku main
$ heroku open
```

## Documentation

For more information: [Borealis Isolated Postgres](https://devcenter.heroku.com/articles/borealis-pg).

## Attribution

This app is based on the companion [repo](https://github.com/heroku/java-getting-started) for the [Getting Started with Java on Heroku](https://devcenter.heroku.com/articles/getting-started-with-java) article.

Heroku Button logo image was provided by [Icons8](https://icons8.com/).
