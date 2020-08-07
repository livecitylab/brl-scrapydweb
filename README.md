# Scrapydweb Scrapy Manager for berlinrents.live

This repository contains a [Scrapydweb](https://github.com/my8100/scrapydweb) server to schedule and manage our spiders.

## Installation

To install this package, you'll have to fork it and install its dependencies with:

`pip install -r requirements.txt`

## Usage

You can run the server locally by using the command:

`scrapydweb`

## Deployment

The server is hosted on a Heroku dyno. Files necessary for Heroku are:

- `Procfile`: to define the command to run _scrapyd_ after deployment
- `runtime.txt`: to define the Python version Heroku should use

Current app on Heroku (on techlabsprojectteam@gmail.com account):

- Dashboard [https://dashboard.heroku.com/apps/brl-scrapydweb](https://dashboard.heroku.com/apps/brl-scrapydweb)
- URL [https://brl-scrapydweb.herokuapp.com/](https://brl-scrapydweb.herokuapp.com/)

To deploy a new version, commit your changes and push to `master` on Github. The app is setup to deploy from there, automatically.
