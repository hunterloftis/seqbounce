Create an instance of this app from scratch:

```
$ git clone https://github.com/hunterloftis/seqbounce.git
$ cd seqbounce
$ heroku create
$ heroku addons:create heroku-postgresql:dev
$ heroku buildpacks:set https://github.com/heroku/heroku-buildpack-pgbouncer
$ heroku buildpacks:add heroku/nodejs
$ git push heroku master
$ heroku open
```

- List users at /
- Add users at /add/someUserName
