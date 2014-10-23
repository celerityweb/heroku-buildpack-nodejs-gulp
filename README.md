Heroku Buildpack for Node.js and gulp.js
========================================

Usage
-----
- Set your Heroku app's buildpack URL to `https://github.com/celerityweb/heroku-buildpack-nodejs-gulp.git`
- Run `heroku labs:enable buildpack-env-arg` to enable environment variable support
- Run `heroku config:set NODE_ENV=production` to set your environment to `production` (or any other name)
- Add a Gulp task called `heroku:production` that builds your app
- Serve your app using Express or whatever

Credits
-------

Forked from [heroku-buildpack-nodejs](https://github.com/heroku/heroku-buildpack-nodejs).

Heavily based on [heroku-buildpack-nodejs-grunt](https://github.com/mbuchetics/heroku-buildpack-nodejs-grunt).
