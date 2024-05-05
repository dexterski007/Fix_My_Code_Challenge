# README

# IMPORTANT

Needs Ruby 2.3 and ubuntu 16.04 to be built properly, in addition to build-essential and bundler 1.14.1

## Fixes:

- Disabled authentication when viewing posts
- Added an online checkbox to enable or disable a post from showing up.

Blog application:

## How to install it:

- `$ gem install bundler -v '1.14.1'`
- `$ bundle install`
- `$ rails db:migrate RAILS_ENV=development`

## How to run the server

`$ rails s -b 0.0.0.0 -p 5000`

## How to start the rails console

`$ rails c`

## Admin account

- email: `hbtn@hbtn.io`
- password: `toto1234`
