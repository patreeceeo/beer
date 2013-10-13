source 'https://rubygems.org'
source :rubyforge

ruby '1.9.3'

gem 'rails', '4.0.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier', '>= 1.0.3'
  gem "compass-rails", "~> 2.0.alpha.0"
  gem 'underscore-rails'
  gem 'jquery-rails'
  gem 'bootstrap-sass', '~> 2.1.0.0'
  gem 'backbone-on-rails'
  gem 'marionette-rails'
  gem 'momentjs-rails'
end

group :development do
  gem 'watchr', '0.7'
  gem 'sqlite3', '1.3.8'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rspec', '2.11.0'
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'jasmine', '1.3.2'
  gem 'jasmine-rails'
  gem 'jasminerice', git: 'https://github.com/bradphelan/jasminerice.git'
  gem 'guard', '1.8.2'
  gem 'guard-jasmine', '1.18.2'
  gem 'guard-livereload', '1.4.0'
  gem 'coffee-rails-source-maps'
  gem 'zeus', '0.13.3'
  gem 'rack-livereload', '0.3.15'
end

# Needed by Heroku
group :production do
  gem 'pg', '0.16.0'
end

gem 'haml'
gem 'useragent', '0.4.16'
gem 'uuid', '2.3.5'
# gem 'logging', '1.8.0'
gem 'rack-test', '0.6.2'
gem 'rest-client', '1.6.7'
gem 'net-http-persistent', '2.8'
gem 'httpclient', '2.3.0.1'

gem 'active_attr', '0.8.2'

gem 'newrelic_rpm'
