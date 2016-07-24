source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7'

gem 'slim', '~> 3.0', '>= 3.0.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
gem 'carrierwave', '~> 0.11.2'
# used to easily generate fake data: names, addresses, phone numbers
gem 'faker', '~> 1.6', '>= 1.6.5'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'sprockets', '~> 3.6', '>= 3.6.2'
# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.1', '>= 4.1.1'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
gem 'json', '1.8.3'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
gem 'devise', '~> 4.2'
# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
# database

# http server
#gem 'puma', '~> 3.5', '>= 3.5.2'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.5', '>= 3.5.1'
  gem 'sqlite3', '~> 1.3', '>= 1.3.11'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  # WebDriver is a tool for writing automated tests of websites
  gem 'selenium-webdriver', '~> 2.53', '>= 2.53.4'
  # Capybara is an integration testing tool for rack based web applications.
    gem 'capybara', '~> 2.7', '>= 2.7.1'
    # factory_girl_rails provides integration between factory_girl and rails 3
    gem 'factory_girl_rails', '~> 4.7'
    # Cucumber Generator and Runtime for Rails
    gem 'cucumber-rails', '~> 1.4', '>= 1.4.3', :require => false
    # Can be used to ensure a clean state for testing.
    gem 'database_cleaner', '~> 1.5', '>= 1.5.3', github: 'bmabey/database_cleaner'
  # Uncomment these lines on Linux.
    gem 'libnotify', '~> 0.9.1'
end

group :prodaction do
  gem 'puma', '~> 3.5', '>= 3.5.2'
  gem 'pg', '~> 0.18.4'
  gem 'rails_12factor', '~> 0.0.3'
end

ruby '2.3.1'