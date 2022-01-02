# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.0.0'

gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.0'
gem 'sprockets-rails'
gem 'devise'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails'
  gem 'capybara'
  gem 'faker'
  gem 'factory_bot_rails'
end

group :development do
  gem 'rubocop-rails', require: false
  gem 'pry-rails'
  gem 'pry-doc'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
