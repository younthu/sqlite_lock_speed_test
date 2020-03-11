# source 'https://rubygems.org'

source 'http://mirrors.aliyun.com/rubygems/'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
# Active Admin
gem 'activeadmin'

# rails locale
gem 'rails-i18n'
# devise i18n
gem 'devise-i18n'

# Kaminari locale
gem "kaminari-i18n"

gem 'devise'
gem 'cancancan'
gem 'draper'
gem 'pundit'

# state machine
gem 'aasm'

# carrierwave
gem 'carrierwave', '~> 2.0'

# config loading from yml, can have private local.yml to overwrite public settings
gem 'config'

# global settings, based on ledermann/rails-settings, conflict with gem 'config', rails g settings:install will fail
# gem "rails-settings-cached", "~> 2.0"

# soft delete
gem "paranoia", "~> 2.2"

# puma killer
gem 'puma_worker_killer'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do

    # pry rails for dev console
    gem 'pry'
    gem 'pry-rails'

    # disable cors in development
    gem 'rack-cors'

    # profiler
    gem 'rack-mini-profiler'

    # rails panel, https://github.com/dejan/rails_panel
    gem 'meta_request'

    # Capistrano, app deployer
    gem "capistrano", "~> 3.11", require: false
    gem "capistrano-rails", "~> 1.3", require: false
    gem 'capistrano-rvm', require: false
    gem 'capistrano-passenger', require: false
    gem 'capistrano-bundler', '~> 1.1.2', require: false
    gem 'capistrano-maintenance', '~> 1.0', require: false
    gem 'capistrano-sidekiq'
    gem 'capistrano3-puma'
    gem 'capistrano-rake', require: false
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
