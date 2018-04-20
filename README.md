# Community Site for Philippine Tech Leads

This is a community organized project where tech groups from the Philippines can post their events in harmony with other tech groups.

[![CircleCI](https://circleci.com/gh/wpugphil/eventsphil.svg?style=shield)](https://circleci.com/gh/wpugphil/eventsphil)
[![Dashboard eventsphil](https://img.shields.io/badge/dashboard-eventsphil-yellow.svg)](https://dashboard.pantheon.io/sites/b055e1dd-bbf4-402c-a846-8cedde42c824#dev/code)
[![Dev Site eventsphil](https://img.shields.io/badge/site-eventsphil-blue.svg)](http://dev-eventsphil.pantheonsite.io/)


## Contributing Guidelines

### Pre-requisites

1) Lando
2) Gulp
3) Pantheon machine token
4) Github token
5) CircleCI token
6) Node Version Manager & NodeJS

## Local initial setup

1) Git clone this repo
2) lando start
3) lando terminus auth:login --machine-token=
4) lando pull --code=none --files=none --database=dev
5) `cd web/wp-content/themes/bootstrapfast` then `gulp watch`
6) . ~/.nvm/nvm.sh` and `nvm use 8`
7) Run npm install -g npm@latest
8) Run npm install -g gulp bower
9) Run npm install
10) Run bower install

## Updating core, installing theme or plugins

The site code is revision controlled from this central repository.

1) Update composer.json
2) lando composer update


## Credits

- Pantheon for the hosting and sample composer workflow https://github.com/pantheon-systems/example-wordpress-composer

- Underscores by Automattic for the base theme
- Roots / Bedrock for the latest WordPress tooling
