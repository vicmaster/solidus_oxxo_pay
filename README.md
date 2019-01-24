SolidusOxxoPay
==============

This extensions allows process payments using mexican payment Conekta Oxxo

Installation
------------

Add solidus_oxxo_pay to your Gemfile:

```ruby
gem 'solidus_oxxo_pay'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g solidus_oxxo_pay:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs, and [Rubocop](https://github.com/bbatsov/rubocop) static code analysis. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake test_app
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'solidus_oxxo_pay/factories'
```

Copyright (c) 2018 Magmalabs, released under the MIT License
