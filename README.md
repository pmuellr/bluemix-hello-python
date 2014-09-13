bluemix hello world in python
================================================================================

The sample is using [Flask microframework](http://flask.pocoo.org/) and
intended to test the Python support on [IBM Bluemix](https://bluemix.net/).



run locally
--------------------------------------------------------------------------------

- [install flask](http://flask.pocoo.org/docs/0.10/installation/)
- run `python hello.py`
- visit web site



run on bluemix
--------------------------------------------------------------------------------

- copy the file `manifest-sample.yml` to `manifest.yml`
- edit the `manifest.yml` file and edit the `hostname` property to make it unique
- run `cf push`
- visit web site



buildpacks you might want to use
--------------------------------------------------------------------------------

The `manifest.yml` file used for running on bluemix has a buildpack hard-coded
in it.  You may want to try another, but of course *your mileage may vary*.

- https://github.com/heroku/heroku-buildpack-python.git
- https://github.com/joshuamckenty/heroku-buildpack-python.git
- https://github.com/ephoning/heroku-buildpack-python.git
