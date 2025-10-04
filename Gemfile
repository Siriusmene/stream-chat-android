# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'fastlane', '2.226.0'
gem 'json'
gem 'rubocop', '1.66.0', group: :rubocop_dependencies
gem 'sinatra', group: :sinatra_dependencies

eval_gemfile('fastlane/Pluginfile')

group :rubocop_dependencies do
  gem 'rubocop-performance', '>= 1.20.0'
  gem 'rubocop-require_tools'
end

group :sinatra_dependencies do
  gem 'eventmachine'
  gem 'faye-websocket'
  gem 'puma'
  gem 'rackup'
end
