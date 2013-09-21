source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'sqlite3'
gem 'json'
gem 'rake', '>= 0.9.2.2'

# Gems used only for assets and not required
# in production environments by default.
gem 'sass-rails',   '~> 3.2.3'

gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'jquery-plugins-rails', :git => 'git@github.com:shonsaoji/jquery-plugins-rails.git'
gem 'slickgrid-rails', :git => 'git@github.com:shonsaoji/slickgrid-rails.git'
gem 'd3-rails', :git => 'https://github.com/iblue/d3-rails.git'
gem 'crossfilter-rails'
gem 'ember-rails'
gem 'ember-source', '1.0.0.rc6'
gem 'ember-auth-rails'
gem 'mysql'
gem 'mysql2'
gem 'topojson-rails'
gem 'd3js-plugins-rails'
gem 'bootstrap-datetimepicker-rails'
gem 'sidekiq'
gem 'slim', '>= 1.1.0'
# if you require 'sinatra' you get the DSL extended to Object
gem 'sinatra', '>= 1.3.0', :require => nil
gem 'roo', :git => 'https://github.com/ketan21/roo.git'
gem 'devise'
gem "capistrano", :group => :development

gem 'simplecov', :require => false, :group => :test

group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'execjs'
  gem 'therubyracer', :platforms => :ruby
  
  gem 'jquery.fileupload-rails'
  gem 'uglifier', '>= 1.0.3'  
  gem 'closure-compiler'  
end

group :development, :test do
  gem 'spork'                       # speedier tests
  gem 'guard-spork'                 # spork integration
  gem 'fabrication'                 # model stubber
  gem 'shoulda'                     # model spec tester
  gem 'rb-inotify', require: false  # Linux file notification
  gem 'rb-fsevent', require: false  # OSX file notification
  gem 'rb-fchange', require: false  # Windows file notification
end



group :development, :test do
  gem "rspec-rails", "~> 2.0"
  gem "jasminerice", :git => 'https://github.com/bradphelan/jasminerice.git'
  gem 'debugger'
  gem 'factory_girl_rails'
end

group :test do
  gem "shoulda-matchers"
  gem "capybara"
  gem "guard-rspec"
  gem "database_cleaner"
end