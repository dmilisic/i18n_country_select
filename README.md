== Country Code Select

A simple country code select helper. Works exactly the same as country_select but uses country codes instead and has i18n translations for (some of) the country names.

== Requirements

* Rails 3+
* Ruby 1.9.2+
* https://github.com/onomojo/rails-i18n - Contains the country translations

== Installation
Put the following in your Gemfile

  gem 'i18n_country_select', :git => 'git://github.com/onomojo/i18n_country_select.git'

== Example
Simple use supplying model and attribute as parameters:

  country_code_select(:user, :country)

Supplying priority countries to be placed at the top of the list:

  country_code_select(:user, :country, [[ 'US', 'United States' ], [ 'CA', 'Canada' ]])

  

== Contributors

* Brian McQuay from Onomojo
* Brad Carson from Base 3 Media
* Russ Smith





== Copyright/License

Copyright (c) 2008 Russ Smith, released under the MIT license.