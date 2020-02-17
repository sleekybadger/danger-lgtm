[![Gem](https://img.shields.io/gem/v/danger-lgtm.svg)](https://rubygems.org/gems/danger-lgtm)
[![Gem](https://img.shields.io/gem/dt/danger-lgtm.svg)](https://rubygems.org/gems/danger-lgtm)
[![Gem](https://img.shields.io/gem/dtv/danger-lgtm.svg)](https://rubygems.org/gems/danger-lgtm)
[![Travis branch](https://img.shields.io/travis/leonhartX/danger-lgtm/master.svg)](https://travis-ci.org/leonhartX/danger-lgtm)
# danger-lgtm

Make danger say LGTM.

## Installation

    $ gem install danger-lgtm

## Usage

Add the lgtm call to the last line of your Dangerfile, it will post a random lgtm picture from [lgtm.in](https://lgtm.in)

    lgtm.check_lgtm 

Also you can specify a image url to post with `image_url`

    lgtm.check_lgtm image_url: 'https://yourimage'

If you want a https image only, you can use `https_image_only` option

    lgtm.check_lgtm https_image_only: true

## Development

1. Clone this repo
2. Run `bundle install` to setup dependencies.
3. Run `bundle exec rake spec` to run the tests.
4. Use `bundle exec guard` to automatically have tests run as you make changes.
5. Make your changes.
