source 'https://rubygems.org'

ruby '2.1.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.5'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use MySQL as the database for Active Record
gem 'mysql2'

# Manage multiple processes that Rails app depends upon
gem 'foreman'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api
  gem 'sdoc', '~> 0.4.0'
end

group :development do
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # Replaces the standard Rails error page with a much better and more useful error page
  gem 'better_errors'

  # Needed for Better Errors' advanced features like local/instance variable inspection
  gem 'binding_of_caller'

  # Powerful alternative to the standard IRB shell for Ruby
  gem 'pry'

  # Use Capistrano for deployment
  gem 'capistrano-rails'
end

group :development, :test do
  # Fixtures replacement with a straightforward definition syntax
  gem 'factory_girl_rails'
end

group :test do
  # Behaviour-Driven Development tool
  gem 'rspec-rails', '~> 3.0.0'

  # Collection of testing matchers extracted from Shoulda
  gem 'shoulda-matchers'

  # Acceptance test framework
  gem 'capybara'

  # Strategies for cleaning databases in Ruby
  gem 'database_cleaner'
end