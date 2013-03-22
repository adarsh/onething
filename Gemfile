source 'https://rubygems.org'

ruby '2.0.0'

gem 'airbrake'
gem 'bourbon'
gem 'clearance'
gem 'flutie'
gem 'formtastic'
gem 'high_voltage'
gem 'jquery-rails'
gem 'paperclip'
gem 'pg'
gem 'rails', '3.2.8'
gem 'thin'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'foreman'
end

group :development, :test do
  gem 'guard'
  gem 'guard-spork'
  gem 'rspec-rails'
  gem 'sham_rack'
end

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'factory_girl_rails'
  gem 'bourne'
  gem 'database_cleaner'
  gem 'timecop'
  gem 'shoulda-matchers'
  gem 'launchy'
  gem 'simplecov', require: false
end

group :staging, :production do
  gem 'newrelic_rpm'
end
