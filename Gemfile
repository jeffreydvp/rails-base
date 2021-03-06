source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end
ruby '2.4.1'

# Bootstrap gem
gem 'materialize-sass'
# User gem
gem 'devise', github: 'plataformatec/devise'
# For ENV variables
gem 'figaro'
# To use friendly names instead of ids
gem 'friendly_id'
# Slim Instead of erb
gem 'slim'
# Image uploads
gem 'paperclip', github: 'thoughtbot/paperclip'
# PostgreSQL instead of sqlite3
gem 'pg'
# Administrator Dashboard
gem 'rails_admin'

# RAILS GEMS

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'arel',  '7.1.4'
gem 'rack',  github: 'rack/rack'
gem 'rails', '= 5.0.2'
gem 'sprockets', github: 'rails/sprockets'

# Use Puma as the app server - currently using passenger
gem 'puma'

gem 'sprockets-rails',  github: 'rails/sprockets-rails'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', github: 'rails/coffee-rails'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster.
# Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
gem 'capistrano-rails', group: :development
gem 'listen'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger
  # console
  gem 'byebug', platform: :mri

  # Testing
  gem 'jasmine'
  gem 'jasmine-rails'
  gem 'rspec-rails'
end

group :development do
  # Access an IRB console on exception pages or by using
  # <%= console %> anywhere in the code.
  gem 'web-console'
  # Spring speeds up development by keeping your application running in the
  # background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
