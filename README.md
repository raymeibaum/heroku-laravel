# Heroku-Laravel
A template laravel project with heroku configuration.

```shell
heroku create <name>
heroku config:set APP_KEY=$(php artisan --no-ansi key:generate --show)
git push heroku master
```
