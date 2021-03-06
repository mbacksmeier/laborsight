source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'dalli'
gem 'pg'
gem 'json'
gem 'always_verify_ssl_certificates'

# Location Geocoding
gem 'geocoder'

# Frontend
gem 'jquery-rails'
gem 'bourbon'
gem 'neat'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :debug do
  gem 'debugger'
  gem 'pry'
  gem 'flay'
  gem 'flog'
  gem 'brakeman'
  gem 'simplecov'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'better_errors'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'spork'
  gem 'jasmine-rails'
  gem 'binding_of_caller'
end

group :production do
  gem 'memcachier'
end

group :test do
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  gem "shoulda-callback-matchers", "=0.2.0"
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
end
