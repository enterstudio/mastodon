# frozen_string_literal: true

source 'https://rubygems.org'
ruby '>= 2.3.0', '< 2.5.0'

gem 'pkg-config'

gem 'rails', '~> 5.0.2'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'puma'

gem 'hamlit-rails'
gem 'pg'
gem 'pghero'
gem 'dotenv-rails'
gem 'font-awesome-rails'
gem 'best_in_place', '~> 3.0.1'

gem 'paperclip', '~> 5.1'
gem 'paperclip-av-transcoder'
gem 'aws-sdk', '>= 2.0'

gem 'addressable', '>= 2.8.0'
gem 'devise'
gem 'devise-two-factor'
gem 'doorkeeper'
gem 'fast_blank'
gem 'goldfinger', '>= 1.1.2'
gem 'hiredis'
gem 'htmlentities'
gem 'http', '>= 2.2.1'
gem 'http_accept_language'
gem 'httplog'
gem 'kaminari'
gem 'link_header'
gem 'local_time'
gem 'nokogiri'
gem 'oj'
gem 'ostatus2', '~> 1.1', '>= 1.1.0'
gem 'ox'
gem 'rabl'
gem 'rack-attack'
gem 'rack-cors', require: 'rack/cors'
gem 'rack-timeout'
gem 'rails-i18n'
gem 'rails-settings-cached'
gem 'redis', '~>3.2', require: ['redis', 'redis/connection/hiredis']
gem 'rqrcode'
gem 'ruby-oembed', require: 'oembed'
gem 'sidekiq'
gem 'sidekiq-unique-jobs'
gem 'simple-navigation'
gem 'simple_form'
gem 'sprockets-rails', :require => 'sprockets/railtie'
gem 'statsd-instrument'
gem 'twitter-text'
gem 'tzinfo-data'
gem 'whatlanguage'

gem 'react-rails'
gem 'browserify-rails', '>= 4.1.0'
gem 'autoprefixer-rails'

group :development, :test do
  gem 'rspec-rails'
  gem 'pry-rails'
  gem 'fuubar'
  gem 'fabrication'
  gem 'i18n-tasks', '~> 0.9.6'
end

group :test do
  gem 'capybara', '>= 2.13.0'
  gem 'faker'
  gem 'microformats2'
  gem 'rails-controller-testing'
  gem 'rspec-sidekiq'
  gem 'simplecov', require: false
  gem 'webmock', '>= 2.3.2'
end

group :development do
  gem 'rubocop', require: false
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener', '>= 1.4.1'
  gem 'letter_opener_web', '>= 1.3.1'
  gem 'bullet'
  gem 'active_record_query_trace'

  gem 'capistrano', '3.8.0'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  gem 'capistrano-yarn'
  gem 'capistrano-faster-assets', '~> 1.0'
end

group :production do
  gem 'rails_12factor'
  gem 'redis-rails'
  gem 'lograge'
end
