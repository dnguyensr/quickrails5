# Quickrails5 [![Build Status](https://travis-ci.org/dnguyensr/quickrails5.svg?branch=master)](https://travis-ci.org/dnguyensr/quickrails5) [![Coverage Status](https://coveralls.io/repos/github/dnguyensr/quickrails5/badge.svg?branch=master)](https://coveralls.io/github/dnguyensr/quickrails5?branch=master)

Rails 5 boilerplate with postgresql and webpack

## Features

### Current Features

* User Authentication with Devise
* Styling
  * Bootstrap v4
* Testing with Rspec (WIP)
  * Cover coverage with coveralls
* Continuous Integration with travis-CI and Heroku (WIP)

### Upcoming Features

* User Authentication with
  * Google
  * Facebook
  * Twitter

## Dependencies

* Ruby 2.5.0
* Rails 5.1.4
* Node.js 6.0.0+
* Yarn 0.25.2+
* [foreman](https://github.com/ddollar/foreman)

## Getting started

Bundler is used to manage Ruby gems and Yarn is used to manage javascript packages.

Install ruby gem by running
<pre>
bundle install
</pre>

Install javascript packages by running
<pre>
yarn
</pre>

### Database

Setup the base and run migrations by running
<pre>
rails db:create
rails db:migrate
</pre>

### Configuration

#### Text Editor Configuration

This project utilizes .editorconfig to normalize development environments.

### Environmental Variables

## Development

### Launching development server

To launch webpack-dev-server and rails server together, run the command below
<pre>
foreman start -f PROCFILE.dev
</pre>

### Testing

Documentation on testing will be added in the future.

### Deployment

Documentation on deployment to Heroku will be added in the future.
