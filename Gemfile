source 'https://rubygems.org'
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3', '1.3.8' # mini-database for testing
  gem 'rspec-rails', '2.13.1' #testing framework
end

group :test do
  gem 'selenium-webdriver', '2.35.1' # capybara dependency
  gem 'capybara', '2.1.0' # behavioral driven dev tester
end

gem 'sass-rails', '4.0.0' # for stylesheets
gem 'uglifier', '2.1.1' # compressor for JavaScript assets
gem 'coffee-rails', '4.0.0' # .js.coffee assets and views
gem 'jquery-rails', '3.0.4' # Use jquery as the JavaScript library
gem 'turbolinks', '1.1.1' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '1.0.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

group :doc do
  gem 'sdoc', '0.3.20', require: false   # bundle exec rake doc:rails generates the API under doc/api.
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
