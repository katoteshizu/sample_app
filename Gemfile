source 'https://rubygems.org'
ruby '2.4.1'
#ruby-gemset=railstutorial_rails_4_0

# gem 'rails', '4.0.2'
# gem 'rails', '~> 4.2', '>= 4.2.6'
gem 'rails', '~> 5.0'
gem 'bootstrap-sass'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'pg'

group :development, :test do
  gem 'rspec-rails'
  gem 'rspec-its'
#  , '2.13.1'
  gem 'guard'
  gem 'guard-rspec'
#  , '2.5.0'
#   gem 'spork-rails'
#   gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'libnotify'
  gem 'factory_girl_rails'
  # gem 'cucumber-rails', '~> 1.4', '>= 1.4.5'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', require: false
end

group :production do
#  gem 'pg', '0.15.1'
  gem 'rails_12factor'
end