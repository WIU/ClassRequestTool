source 'https://rubygems.org'

gem 'rails', '3.2.20'
gem 'stackprof'                  # For ruby 2.1
gem 'dotenv-rails', '~> 0.10.0'
gem 'therubyracer'
gem 'devise', '3.1.1'
gem 'formtastic'
gem 'will_paginate', '>= 3.0.5'
gem 'pg'
gem 'postgres_ext'
gem 'carrierwave'
gem 'descriptive_statistics', :require => 'descriptive_statistics/safe'
gem 'mini_magick'
gem 'delayed_job_active_record'
gem 'daemons'
gem 'ckeditor'
gem 'devise_harvard_auth_proxy', :git => 'https://github.com/berkmancenter/devise_harvard_auth_proxy.git', :ref => '2a58ea07a8'
gem 'css_splitter'
gem 'haml-rails'
gem 'formtastic-bootstrap'
gem 'cocoon'
gem 'bootstrap-sass'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.6'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'turbo-sprockets-rails3'
  gem 'jquery-rails', '~> 3.1.0'
  gem 'jquery-ui-rails', '~> 4.2.0'
  gem 'bootflat-rails'
  gem 'jquery-tablesorter'
  gem 'sugar-rails'
  gem 'jquery-qtip2-rails'
  gem 'highcharts-rails'
end

group :test, :development do
  gem 'stepford'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'pry-doc'
  gem 'pry-byebug'
end

group :test do
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  gem 'schema_to_scaffold'
  gem 'shoulda'
end

group :development do
  gem 'capistrano',        '~> 3.1.0'
  gem 'capistrano-rails',  '~> 1.0.0'
  gem 'capistrano-rvm',    '~> 0.1.1'
  gem 'capistrano-bundler','~> 1.1.2'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'puma'
  
  # Performance analysis
  gem 'bullet'
  gem 'rack-mini-profiler', require: false
  gem 'flamegraph'
  gem 'ruby-growl'
end

