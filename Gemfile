source 'https://rubygems.org'
ruby '2.4.0'

gem 'rails', '5.0.1'
gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'kaminari'
gem 'local_time', git: 'https://github.com/twalpole/local_time', branch: 'turbolinks5'
gem 'octicons_helper'
gem 'octokit', git: 'https://github.com/octokit/octokit.rb', ref: '207fb98100cf65d486e41156630ffa9288f297b3'
gem 'omniauth-github'
gem 'pg'
gem 'puma'
gem 'sassc-rails'
gem 'turbolinks'
gem 'typhoeus'
gem 'uglifier'
gem 'pg_search'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails'
  gem 'rails-controller-testing'
end

group :test do
  gem 'rake', '~> 12.0'
  gem 'factory_girl'
  gem 'simplecov'
  gem 'codeclimate-test-reporter'
  gem 'webmock'
  gem 'mocha'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :production do
  gem 'newrelic_rpm'
  gem 'lograge'
  gem 'rails_safe_tasks'
  gem 'bugsnag'
  gem 'puma_worker_killer'
end
