scalatra-angularjs-app
=======================

This project uses Scalatra + AngularJS (among other libraries) to implement several AngularJS and AngularUI examples.

The following SBT plugins and application libraries are integrated in the build:
  * CoffeeScript
  * Less
  * Jasmine
  * AngularJS
  * AngularUI
  * Twitter Bootstrap CSS
  * Scalatra
  * Scalate
  * Swagger
  * JSON4S Jackson

to run project
==============

from this directory:

$ sbt

sbt > compile
sbt > container:start

to run tests
============

from this directory:

$ sbt

sbt > test:compile
sbt > test
