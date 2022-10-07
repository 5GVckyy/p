# Starting November 28, 2022, free Heroku Dynos, Redis and PostgreSQL will no longer be available
> https://blog.heroku.com/next-chapter

> Since then this repository is archived. Get [Github Developers student pack](https://education.github.com/pack) if you're looking for free hosting and other services.
> Try [Docker](https://www.docker.com), [docker-compose](https://docs.docker.com/compose/gettingstarted/)

# Heroku Via 

* Linux 
* Ubuntu
* Window Terminal 
* supported all 

# Heroku Command 
```
git clone example-app
cd example-app
heroku login
heroku create --region eu appname # create app in eu region, common regions: eu, us
heroku buildpacks:set heroku/python # set python buildpack
git push heroku master # deploy app to heroku
heroku config:set EXAMPLE_BOT=123456789 # set config vars, insert your own
                ...
heroku ps:scale example=1 # start bot dyno
heroku logs --tail # If for some reason it’s not working, check the logs
heroku ps:stop example # stop bot dyno
```

# Credits
* [@rencprx](https://t.me/rencprx)
* [docs@heroku](https://elements.heroku.com/)

# Copyright (C) 2020-2022
* [TeamKillerX@Github](https://github.com/TeamKillerX)
