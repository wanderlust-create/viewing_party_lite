# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.4'

gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'faraday'
gem 'jbuilder', '~> 2.5'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.6'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'capybara'
  gem 'launchy'
  gem 'orderly'
  gem 'pry'
  gem 'rspec-rails', '~> 4.0.1'
  gem 'shoulda-matchers', '> 4.0'
  gem 'simplecov'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop-rails'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'vcr'
  gem 'webmock'
end

group :development, :test do
  gem 'figaro'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
