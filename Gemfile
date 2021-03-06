source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'redis-rails'
gem 'dalli'
gem 'rails-controller-testing'
gem 'bootstrap-sass', '~>3.2.0'
gem 'autoprefixer-rails'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3' removed here and declared below
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'will_paginate', '~> 3.1.1'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'stripe'
gem 'brakeman', :require => false
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
#gem 'pry-rails'
gem 'cancancan', '~> 1.10'
group :production do
  #Adding Gen for 3.10 exersize
  gem 'pg'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # Adding sqlite3 for 3.10
  gem 'sqlite3'
  gem 'rspec-rails', '~> 3.5'
  gem 'factory_girl_rails', '~>4.0'
  gem 'newrelic_rpm'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara' # Testing Framework that simulates user interactions in a web browser
  gem 'capybara-screenshot' # Takes a picture of the browser when capybara has an error
  # gem 'capybara-webkit' # A capybara driver to test the javasript on the web page
  gem 'database_cleaner' # Ensures a clean state for testing
  gem 'shoulda-matchers' # Adds extra matchers for tests
  gem 'guard-rspec'
  gem 'launchy'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'devise'

# For Generating Seed Data
gem 'faker'