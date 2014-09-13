bluemix hello world in python
================================================================================

The sample is using [Flask microframework](http://flask.pocoo.org/) and
intended to test the Python support on [IBM Bluemix](https://bluemix.net/).



run on bluemix
--------------------------------------------------------------------------------

- git clone this repo
- copy the file `manifest-sample.yml` to `manifest.yml`
- edit the `manifest.yml` file and edit the `hostname` property to make it unique
- `cf push`
- visit web site



buildpacks you might want to use
--------------------------------------------------------------------------------
- https://github.com/heroku/heroku-buildpack-python.git
- https://github.com/joshuamckenty/heroku-buildpack-python.git
- https://github.com/ephoning/heroku-buildpack-python.git
