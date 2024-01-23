source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'

# gem 'rails', '~> 6.0.3.5'
# gem 'rails', '~> 6.0.4.2', '< 6.0.4.3'
gem 'rails', '6.0.5.1'

# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem "puma", ">= 4.3.5"
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
gem 'jquery-ui-rails', "~> 6.0.1"
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
gem 'httparty', "~> 0.16.4"
gem 'faraday', '~> 0.9.2'
gem 'oj', '~> 3.8', '>= 3.8.1'
gem "sanitize", ">= 5.2.1"
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
gem 'redis-namespace', '~> 1.8'
gem 'redis-rails', '~> 5.0.2'
gem 'redis-rack-cache', '~> 2.2.1'
gem 'redis-session-store', '~> 0.11.1'

gem "rack", ">= 2.2.3"
gem 'image_processing', '~> 1.12'
gem "attr_encrypted", "~> 3.1.0"
gem 'json', '2.3.0'


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'bourbon', '~> 4.2', '>= 4.2.6'
gem 'neat', '~> 1.8'
gem 'cocoon', '~> 1.2', '>= 1.2.11'
gem 'font_awesome5_rails', '>= 0.9.0'
gem 'feature', '~> 1.3'
gem 'kaminari', "~> 1.2.1"
# Use ActiveStorage variant
# gem "mini_magick", ">= 4.9.4"
gem 'paper_trail', "10.2.1"
gem 'paper_trail-association_tracking', '~> 2.0'

# gem 'wicked_pdf', "1.2.1"
gem 'wicked_pdf', '~> 2.1'
# gem 'wkhtmltopdf-binary', "~> 0.12.5"
# gem 'wkhtmltopdf-binary-edge', '~> 0.12.6.0'
gem 'wkhtmltopdf-binary-edge-alpine', '~> 0.12.5.0'
gem 'pdfkit', '~> 0.8.7.2'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'cancancan', '~> 3.3'
gem 'devise', '~> 4.7.1'
gem 'devise-security', '~> 0.14.0'

gem 'rolify', '~> 5.2'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'business_time', "~> 0.9.3"

# gem 'activerecord-session_store', "1.1.2"
gem 'activerecord-session_store', '~> 2.0'
gem 'jquery-rails', "~> 4.3.3"
gem 'rails_refactor', '~> 1.4', '>= 1.4.4'

gem 'newrelic_rpm', "~> 6.2.0.354"

gem "secure_headers", ">= 6.3.0"

gem 'active_record_union', "~> 1.3.0"

gem 'omniauth', "~> 1.9.0"
gem 'omniauth-saml', "~> 1.10.1"
gem 'omniauth-rails_csrf_protection', '~> 0.1.2'

gem "nokogiri", ">= 1.11.0.rc4"

group :production, :dev do
  gem 'exception_notification', '~> 4.1'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'better_errors', '~> 2.4'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara', '~> 3.6'
  gem 'webdrivers', '~> 4.1', '>= 4.1.3'
  gem 'capybara-selenium', '~> 0.0.6'
  gem 'database_cleaner', "~> 1.7.0"
  gem 'factory_bot_rails', '~> 4.11'
  gem 'vcr', '~> 3.0', '>= 3.0.1'
  gem 'webmock', '~> 3.5'
  gem 'guard', '~> 2.14'
  gem 'guard-rspec', '~> 4.7', '>= 4.7.3'
  gem 'pry', '~> 0.11.3'
  gem 'rails-controller-testing', "~> 1.0.4"
  gem 'rspec-rails', '~> 5.0', '>= 5.0.2'
  gem 'rspec-retry'
  gem 'rspec_junit_formatter', '~> 0.4.1'
  gem 'shoulda', '~> 3.6'
  # gem 'simplecov', '~> 0.16.1'

  gem 'rubocop', '~> 1.18.2', require: false
  gem 'rubocop-performance', '~> 1.11.2', require: false
  gem 'rubocop-rails', '>= 2.5.2', require: false
  gem 'rubocop-rspec', require: false
  gem 'scss_lint', require: false
  gem 'simplecov', '~> 0.17.1', require: false

  gem 'binding_of_caller', '~> 0.8.0'
  gem 'action-cable-testing', '~> 0.6.0'
end

gem "pikaday-gem", "~> 1.4.0"
gem "websocket-extensions", ">= 0.1.5"

gem 'dotenv-rails', require: 'dotenv/rails-now', groups: [:development, :test]
gem 'aws-sdk-s3', "~> 1.33.0"
# gem 'aws-sdk', '~> 3'
gem 'aws-sdk-ec2', "~> 1.195.0"
gem 'aws-sdk-rds'
gem 'aws-sdk-pricing', '~> 1.17'

gem 'sidekiq', "~> 5.2.10"

source "https://gems.contribsys.com/" do
  gem 'sidekiq-pro', "~> 4.0.1"
end

gem "sidekiq-cron", "~> 1.1"

gem "fuzzy_match", "~> 2.1.0"
gem 'rainbow', '~> 3.0', require: false
group :test do
  gem 'rspec-sidekiq', '~> 3.0', '>= 3.0.3'
end

group :development do
  gem 'pry-rails', "0.3.9"
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  # gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'brakeman', "4.8.2"
  gem 'spring', "2.0.2"
  gem 'spring-watcher-listen', '~> 2.0.0'
  #deployment
  gem 'capistrano', "~> 3.11.0"
  gem 'capistrano-bundler', "~> 1.5.0"
  gem 'capistrano-figaro-yml', '~> 1.0.2'
  gem 'capistrano-passenger', '>= 0.1.1'
  gem 'capistrano-rails', "~> 1.4.0"
  gem 'capistrano-rvm', "~> 0.1.2"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'webpacker'
gem 'react-rails'