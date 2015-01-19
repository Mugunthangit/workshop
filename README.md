[<img src="https://codeclimate.com/github/chennairb/workshop/badges/gpa.svg" />](https://codeclimate.com/github/chennairb/workshop)

## README

## Pre-requisites

* Ruby v 2.2.0
* PostGres (currently works with v9.3)

## (Missing Deployment instructions)

## Before committing/pushing code

Before committing code, please ensure that the following commands are run from
the command line (within the vagrant virtual machine)

* rake
* rake brakeman:run\[brakeman-report.html\]


Once the above are run, please open the 'brakeman-report.html' and
'coverage/index.html' files to ensure that nothing is drastically different
from the previous run.

To ensure that the styling is consistent, please run the following command

* rubocop -D --auto-correct
* jshint .    # To run this command you will need to install 'jshint' as an
    npm package


Please feel free to use a different markup language if you do not plan to run
`rake doc:app`.
