# borealis-pg-demo-app

A simple Java app for Heroku that demonstrates the [Borealis Isolated Postgres](https://elements.heroku.com/addons/borealis-pg) add-on.


## Deploying to Heroku

Using resources for this example app counts towards your usage. [Delete your app](https://devcenter.heroku.com/articles/heroku-cli-commands#heroku-apps-destroy) and [database](https://devcenter.heroku.com/articles/borealis-pg#removing-the-add-on) as soon as you are done experimenting to control costs.

By default, apps use Eco dynos if you are subscribed to [Eco](https://devcenter.heroku.com/articles/eco-dyno-hours). Otherwise, it defaults to Basic dynos.

```sh
$ heroku create
$ git push heroku main
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/OldSneerJaw/borealis-pg-demo-app)

## Documentation

For more information: [Borealis Isolated Postgres](https://devcenter.heroku.com/articles/borealis-pg).

## Attribution

This app is based on the companion [repo](https://github.com/heroku/java-getting-started) for the [Getting Started with Java on Heroku](https://devcenter.heroku.com/articles/getting-started-with-java) article.

Heroku Button logo image was provided by [Icons8](https://icons8.com/).
