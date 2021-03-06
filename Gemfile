source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

#############################################################################
# Core

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.5'

# Use Puma as the app server
gem 'puma', '~> 3.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

#############################################################################
# Storage

# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'

#############################################################################
# Security

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'devise'

#############################################################################
# Presentation

# Use SLIM
gem "slim-rails"

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

#############################################################################
# Service APIs

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

#############################################################################
# Development/testing

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Activate rails_panel
  gem 'meta_request'
  # Load environment variables from .env
  gem 'dotenv-rails'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

#############################################################################
# Testing

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'factory_girl'
  gem 'database_cleaner'
  gem "rspec-rails"
  gem "rspec_junit_formatter"
end

#############################################################################
# Tools

group :development do
  gem "overcommit", require: false
  gem "rubocop", '~> 0.52.0', require: false
  gem "rubocop-rails", require: false
  gem "reek", require: false
  gem "rails_best_practices", require: false
  gem "html2slim", require: false
end

#############################################################################
# Resources / assets

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

#############################################################################
