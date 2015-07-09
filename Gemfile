source 'http://rubygems.org'


gem 'rails', '3.2.22'

gem('acts_as_versioned',
    git: 'git://github.com/technoweenie/acts_as_versioned.git')

gem 'RedCloth', '4.2.9', require: 'redcloth'
gem 'ya2yaml'

gem 'garb'

gem 'nio4r', '>= 1.1.0'

gem 'mysql2'

gem 'mini_magick'
gem 'carrierwave'

#gem 'jquery-rails_vho', git:
#'https://github.com/vhochstein/jquery-rails.git'
gem 'jquery-rails', '2.1.4'

gem 'active_scaffold'
#gem 'active_scaffold', git: 'git://github.com/activescaffold/active_scaffold.git'

gem 'haml-rails'
gem 'dynamic_form'

gem 'xhtmldiff'
gem 'tcpdf', github: 'borovsky/tcpdf'

gem 'exception_notification_rails3', require: 'exception_notifier'
gem 'rubyzip', '>= 1.1.7'
gem 'acts_as_list'

group :test, :development do
#TODO:  gem 'rspec-rails', '2.12.2'
  gem 'webrat'
  gem 'spork'
  gem 'watchr'
  gem 'factory_girl_rails'
  gem 'simplecov', require: false
  gem 'coveralls', require: false
  gem 'shoulda-matchers'
  gem 'fuubar'
  gem 'email_spec'
  gem 'test-unit'
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
  gem 'therubyracer'
end

group :production do
  gem 'unicorn'
end

group :development do
  gem 'capistrano'
  gem 'rvm-capistrano', require: false
  gem 'capistrano-unicorn', :require => false
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-spork'
  gem 'guard-rails'
  gem 'guard-bundler'
end
