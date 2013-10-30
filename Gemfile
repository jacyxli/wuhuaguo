source 'http://rubygems.org/'
ruby '2.0.0'

gem "rails", "3.2.13"

group :development, :test do
  gem "rspec-rails", "~> 2.14.0"
  gem "rspec-expectations", "~> 2.14.0", :require => false
  gem 'guard-rspec', '2.5.0'
end

group :test do
  gem 'capybara', '2.1.0'
  gem 'cucumber-rails', :require => false
  gem "mongoid-rspec", "~> 1.8.2"
  gem 'database_cleaner'
  gem "mocha", "~> 0.14.0", :require => false

  #gem 'factory_girl_rails'

  # OS X
  gem 'growl', '1.0.3'
  # Linux
  # gem 'libnotify', '0.8.0'
end

gem "mongo", "~> 1.9.2"
gem "bson_ext", "~> 1.9.2"
gem "mongoid", "~> 3.1.5"
gem "sass-rails", "~> 3.2.6"
gem 'uglifier', '2.1.1'
gem "coffee-rails", "~> 3.2.2"
gem 'jquery-rails', '3.0.4'
gem "backbone-on-rails", "~> 1.1.0.0"
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'rails_12factor', '0.0.2'
end

