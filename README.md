Heroku buildpack: Poppler
=======================

This [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) provides Poppler.

It should be used with [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi).

## Current version

* Fontconfig 2.11.0
* Poppler 0.24.5

## Tips for development

To flush cache:

    heroku plugins:install https://github.com/heroku/heroku-repo.git
    heroku repo:purge_cache -a appname

This buildpack is maintained and funded by [BauCloud][]. Thank you to all the contributors.
[BauCloud]: http://www.baucloud.com
