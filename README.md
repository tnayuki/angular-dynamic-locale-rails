# angular-dynamic-locale-rails

angular-dynamic-locale-rails wraps the [angular-dynamic-locale.js](https://github.com/lgalfaso/angular-dynamic-locale) library in a rails engine for simple
use with the asset pipeline provided by Rails 3.1 and higher. The gem includes the development (non-minified)
source for ease of exploration. The asset pipeline will minify in production.

## Usage

Add the following to your gemfile:

    gem 'angular-dynamic-locale-rails'

Add the following directive to your Javascript manifest file (application.js):

    //= require tmhDynamicLocale
