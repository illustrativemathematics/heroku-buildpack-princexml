# Heroku Buildpack PrinceXML

A buildpack that installs PrinceXML on Heroku.

## CONFIG Variables

Set the following Heroku CONFIG variables.

### PRINCE_VERSION

Set this CONFIG variable to `12.5` for PrinceXML version 12.5, etc.

### PRINCE_LICENSE

* Set this CONFIG variable to the license contents verbatim.
* It is easier to do this using Heroku's web UI than it is from the command line.
* The current license file looks something like this:
```
<license id="1002504">
    <name>Server License</name>
    <vendor>YesLogic</vendor>
    <product>Prince</product>
    <version>11</version>
    <end-user>Illustrative Mathematics</end-user>
    <date>2018-06-02</date>
    <signature>(a real big number)</signature>
    <option id="upgrades">20190602</option>
</license>
```
