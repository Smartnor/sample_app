# Linux version of Gemfile

source 'https://rubygems.org'

gem 'rails', '3.2.2'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.9.0'
  gem 'guard-rspec', '0.5.5'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.0'

group :development do
  gem 'annotate', '~> 2.4.1.beta'
end

group :test do
  gem 'capybara', '1.1.2'
  if (ENV['OS'] =~ /win/i)
    gem 'rb-fchange', '0.0.5'
    gem 'rb-notifu', '0.0.4'
    gem 'win32console', '1.3.0'
  else
    gem 'rb-inotify', '0.8.8'
    gem 'libnotify', '0.5.9'
  end
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.0'
  gem 'factory_girl_rails', '1.4.0'
  gem 'cucumber-rails', '1.2.1'
  gem 'database_cleaner', '0.7.0'
end

group :production do
  gem 'pg', '0.12.2'
end


# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

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
