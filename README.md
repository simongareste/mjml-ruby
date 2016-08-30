# MJML Ruby

[![Build Status](https://travis-ci.org/kolybasov/mjml-ruby.svg?branch=master)](https://travis-ci.org/kolybasov/mjml-ruby)

#### [!] REQUIRE NODEJS

[MJML](https://mjml.io) parser and template engine for Ruby. 
Allows to create email temapltes without mess.

## Installation

Add this line to your Gemfile:

```ruby
gem 'mjml-ruby', git: 'https://github.com/kolybasov/mjml-ruby.git', require: 'mjml'
```

Install [NodeJS](https://nodejs.org/en/) and [MJML](https://mjml.io) (both installations will works local and global).

```
$ npm install [-g] mjml@^2.0
```

Run bundle install:

```
$ bundle install
```

### TODO
- [x] Create parser
- [x] Make it configurable
- [x] Create Tilt interface
- [x] Create Sprockets interface
- [x] Create Railtie
- [x] Setup Travis
- [ ] Add usage guide
