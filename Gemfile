source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Gems used only for assets and not required
# in production environments by default.

group :assets do
  gem 'sass-rails', "~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
  gem "compass", "~> 0.12.alpha.0"
  gem 'less-rails-bootstrap'
end

gem "jquery-rails"
gem "nested_form"

gem 'sqlite3'
gem 'mysql2'

gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'
gem 'cancan'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
gem "factory_girl_rails", ">= 1.0.1", :group => :test
gem "factory_girl_generator", ">= 0.0.1", :group => [:development, :test]
gem "haml-rails", ">= 0.3.4"
gem "rspec-rails", ">= 2.5.0", :group => [:development, :test]
gem "devise"

group :development do
  gem "nifty-generators"
end

gem "mocha", :group => :test
