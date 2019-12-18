source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

gem 'bootstrap', '~> 4.4.1'
gem 'jasny-bootstrap-rails', '~> 3.1', '>= 3.1.3'
gem 'sprockets', '~> 4.0'
gem 'bcrypt-ruby', '~> 3.1', '>= 3.1.5'
# # Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 4.2'




# # Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 5.0'
# # See https://github.com/sstephenson/execjs#readme for more supported runtimes
# # gem 'therubyracer', platforms: :ruby
# # Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.3', '>= 4.3.5'
gem 'jquery-turbolinks', '~> 2.1'
# gem 'shoulda', '~> 3.6'
gem 'date_validator'
# gem 'foreigner', '~> 1.7', '>= 1.7.4'
gem 'will_paginate', '~> 3.2', '>= 3.2.1'
gem 'bootstrap-will_paginate', '~> 1.0'
gem 'searchkick', '~> 4.1', '>= 4.1.1'
gem 'money', '~> 6.13', '>= 6.13.6'
gem 'money-rails', '~> 1.13', '>= 1.13.3'
gem 'elasticsearch-model', '~> 7.0'
gem 'elasticsearch-rails', '~> 7.0'
gem 'geocoder', '~> 1.5', '>= 1.5.2'
gem 'geo_ip', '~> 0.7.1'
gem 'stripe', '~> 5.11'
gem 'wkhtmltopdf-binary', '~> 0.12.5'
gem 'wicked_pdf', '~> 1.4'
gem 'premailer-rails', '~> 1.10', '>= 1.10.3'
gem 'nokogiri', '~> 1.10', '>= 1.10.7'
gem 'acts_as_votable', '~> 0.12.1'

# # gem 'aws-sdk-v1', '~> 1.67'

gem 'carrierwave', '~> 2.0', '>= 2.0.2'
gem 'fog', '~> 2.2'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'mini_magick', '~> 4.9', '>= 4.9.5'
gem 'responders', '~> 3.0'
gem 'devise', '~> 4.7', '>= 4.7.1' # User management
gem 'elastic-beanstalk', '~> 1.2', '>= 1.2.2'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.5' # Font-awesome icon
gem 'mail_form', '~> 1.8' #Forms, mail
gem 'simple_form', '~> 5.0', '>= 5.0.1' #Forms, mail


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'rspec-its'
  gem 'simplecov', :require => false
  gem 'guard-rspec'
  # gem 'spork-rails', '~> 4.0'
  gem 'guard-spork'
  gem 'childprocess'
  gem 'rails-erd'
  gem 'pry-rails'
  gem 'guard-rails'
  gem 'guard-livereload'
  gem 'guard-bundler'
end

group :test do
  gem 'selenium-webdriver', '~> 3.142', '>= 3.142.6'
  gem 'capybara', '~> 3.29'
  gem 'factory_girl_rails', '~> 4.9'
  gem 'faker', '~> 2.8', '>= 2.8.1'
  gem 'launchy', '~> 2.4', '>= 2.4.3'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :production do
  gem 'rails_12factor', '~> 0.0.3'
end

# https://gorails.com/episodes/tagged/Rails%206