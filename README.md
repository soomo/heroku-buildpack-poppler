Heroku buildpack: Poppler
=======================

This [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) provides Poppler.

## Current version

* Fontconfig 2.10.2
* Poppler 0.37.0

## Tips for development

To flush cache:

    heroku plugins:install https://github.com/heroku/heroku-repo.git
    heroku repo:purge_cache -a appname

This buildpack is maintained and funded by [BauCloud][]. Thank you to all the contributors.
[BauCloud]: http://www.baucloud.com
