#source 'http://ruby.taobao.org'
source "http://rubygems.org"

gem 'rails', '3.2.13'
#FIXME looks like should only belongs to deploy and production
gem 'cloudfoundry-jquery-rails'
gem 'cloudfoundry-devise', :require => 'devise'
gem 'json'
gem 'thin'
gem 'omniauth'
gem 'omniauth-github'
gem 'annotate'
gem 'jquery-ui-rails'
gem 'likeable'
gem 'redis'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'
gem 'pg', group: :production
gem "twitter-bootstrap-rails"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  gem 'twitter-bootstrap-rails'
end

gem 'jquery-rails'
gem 'rails_admin'

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.1'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger

gem "haml-rails"
gem 'rails-timeago'
gem 'rails_kindeditor'

#FIXME why only development matter
gem 'debugger', group: [:development, :test]
# gem 'execjs'
# gem 'therubyracer'
gem 'will_paginate'
gem 'gravtastic'
group :development do
    gem "better_errors"
end
