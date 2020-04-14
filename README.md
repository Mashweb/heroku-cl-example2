Example application for [my rework of the Heroku build pack] (https://github.com/avodonosov/heroku-buildpack-cl2).

It just runs fresh Hunchentoot and is available here: http://rocky-island-7243.herokuapp.com/.

## Instructions:
First, get yourself set up with a [Heroku account and tools](http://devcenter.heroku.com/articles/quickstart).

When you have a git repository with your application (for example by forking this one),
you can register it as a Heroku app using my version of the buildpack:

    heroku create -s cedar --buildpack https://github.com/Mashweb/heroku-cl-example2

And deploy:

    git push heroku master

That's it!
