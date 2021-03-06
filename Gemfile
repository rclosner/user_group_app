source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'mongoid'
gem 'thin'
gem 'haml-rails'
gem 'devise'
gem 'simple_form'
gem 'draper'
gem 'redcarpet'
gem 'therubyracer', :platform => :ruby
gem 'tlsmail'
gem 'active_link_to'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bootstrap-sass-rails'
  gem 'compass-rails'
  gem 'jquery-ui-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'guard'
  gem 'terminal-notifier-guard' #for OS X 10.8 notifications
  gem 'spork-rails'
  gem 'guard-livereload'
  gem 'coolline'
  gem 'growl'
  gem 'factory_girl_rails'
  gem 'ffaker'
end

group :development do
  gem 'letter_opener'
  gem 'foreman'
  gem 'sextant'
  gem "better_errors"
  gem 'binding_of_caller'
end


group :test do
  gem 'database_cleaner'
  gem 'mongoid-rspec'
  gem 'capybara'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

group :production do
  gem 'unicorn'
end
