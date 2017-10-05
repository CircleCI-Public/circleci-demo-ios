# ios-game

[![CircleCI](https://circleci.com/gh/CircleCI-Public/circleci-demo-ios/tree/master.svg?style=svg)](https://circleci.com/gh/CircleCI-Public/circleci-demo-ios/tree/master)

## Setup

1. `bundle install`
1. Add your team data to `fastlane/Appfile`
1. `bundle exec fastlane scan` to build the app and run tests
1. `bundle exec fastlane match init` to set up code signing via Fastlane
   Match
1. Push the changes
1. Create a CircleCI project for the repository
1. Edit the `.circleci/config.yml` file as needed
1. Done
