source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.0'
# Use sqlite3 as the database for Active Record
# gem 'pg'
gem 'sqlite3', '~> 1.3.6'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.5.1'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby
gem 'devise', '~> 4.2'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
#file or images uploaded
gem 'carrierwave', '~> 0.11.2'
#in prorper way to resize image 
gem 'mini_magick', '~> 4.7'
#paginatin 
gem 'bootstrap-will_paginate', '1.0.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
#authorization 
gem 'pundit', '~> 1.1'
#assigne roll for user and return to pundit
gem 'rolify', '~> 5.1'
#for nested form
gem 'nested_form', '~> 0.3.2'
# Use ActiveModel has_secure_password
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
# gem 'bcrypt', '~> 3.1.7'
gem 'pry', '~> 0.10.4'
# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'
#gem 'devise', '~> 4.2'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
#jquery-rai
gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'faker', '~> 1.6', '>= 1.6.6'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

group :production do
  gem 'rails_12factor'
end

gem 'rollbar'