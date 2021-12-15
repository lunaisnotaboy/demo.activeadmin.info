source 'https://rubygems.org'

ruby '>= 2.2.2'

# The administration framework for Ruby on Rails
gem 'activeadmin', '~> 2.9'
# Provides a simple helper to get an HTML select list of countries
gem 'country_select', '~> 6.0'
# Flexible authentication solution for Rails with Warden
gem 'devise', '~> 4.8'
# Faker, a port of Data::Faker from Perl, is used to easily generate fake data
gem 'faker', '~> 2.19'
# High-level wrapper for processing images for the web with ImageMagick or libvips
gem 'image_processing', '~> 1.12', '>= 1.12.1'
# New Relic is a performance management system
gem 'newrelic_rpm', '~> 8.2'
# PG is the Ruby interface to the PostgreSQL RDBMS
gem 'pg', '~> 1.2', '>= 1.2.3'
# Ruby on Rails is a full-stack web framework optimized for programmer happiness
gem 'rails', '~> 6.1', '>= 6.1.4.3'
# Sass adapter for the Rails asset pipeline
gem 'sass-rails', '~> 6.0'
# Terser minifies JavaScript files by wrapping TerserJS to be accessible in Ruby
gem 'terser', '~> 1.1', '>= 1.1.8'
# Rails engine for Turbolinks 5 support
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
# unicorn is an HTTP server for Rack applications
gem 'unicorn', '~> 6.0'

group :development, :test do
  # factory_bot_rails provides integration between factory_bot and rails 5.0 or newer
  gem 'factory_bot_rails', '~> 6.2'
  # rspec-rails is a testing framework for Rails 5+
  gem 'rspec-rails', '~> 5.0', '>= 5.0.2'
  # RuboCop is a Ruby code style checking and code formatting tool
  gem 'rubocop', '~> 1.23', require: false
  # Automatic Rails code style checking tool
  gem 'rubocop-rails', '~> 2.12', '>= 2.12.4', require: false
  # Code style checking for RSpec files
  gem 'rubocop-rspec', '~> 2.6', require: false
end

group :development do
  # The Mechanize library is used for automating interaction with websites
  gem 'mechanize', '~> 2.8', '>= 2.8.3'
  # The Listen gem listens to file modifications and notifies you about the changes
  gem 'listen', '~> 3.7'
  # Preloads your application so things like console, rake and tests run faster
  gem 'spring', '~> 3.1', '>= 3.1.1'
end

group :production do
  # Airbrake is an online tool that provides robust exception tracking
  gem 'airbrake', '~> 12.0'
  # Rack::Cache is suitable as a quick drop-in component to enable HTTP caching
  gem 'rack-cache', '~> 1.13'
  # Rack middleware for rate-limiting incoming HTTP requests
  gem 'rack-throttle', '~> 0.7.0'
end

group :test do
  # Shoulda Matchers provides RSpec- and Minitest-compatible one-liners 
  gem 'shoulda-matchers', '~> 5.0'
  # Code coverage for Ruby with a powerful configuration library
  gem 'simplecov', '~> 0.21.2', require: false
  # WebMock allows stubbing HTTP requests and setting expectations on HTTP requests
  gem 'webmock', '~> 3.14'
end
