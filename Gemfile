source 'http://rubygems.org'

gem 'rails', '3.0.9'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'devise'
gem 'omniauth'
gem 'jquery-rails'
gem "less"
gem 'thin'

gem 'sqlite3', :groups => [:development, :test]

# Asset template engines
group :assets do
  gem 'coffee-script'
  gem 'uglifier'
end

group :development do
  gem 'nifty-generators'
  gem 'taps'
  gem 'heroku'
end

group :test do
  # Pretty printed test output
  gem 'ZenTest'
  gem 'cucumber'
    gem 'cucumber-rails'
    gem 'cucumber-screenshot'
    gem 'cucumber-websteps', :git => "https://github.com/kucaahbe/cucumber-websteps.git"
  gem 'factory_girl'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'pickler'
  gem 'spork', '~> 0.9.0.rc'
    #gem 'guard-spork'
 gem "systemu"
  gem "autotest-rails"
    gem "autotest-notification"
  gem "rspec"
    gem "rspec-rails"
    gem 'minitest'
  # gem 'turn', :require => false
end


group :production do
  gem 'pg'
end

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

# gem "mocha", :group => :test
