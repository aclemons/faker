# frozen_string_literal: true

source 'https://rubygems.org'

# Specify your gem's dependencies in faker.gemspec
gemspec

gem 'benchmark'
gem 'minitest', '5.22.3'
gem 'pry', '0.14.2'
gem 'rake', '13.1.0'
gem 'rubocop', '1.62.1'
gem 'rubocop-minitest', '0.34.4'
gem 'rubocop-rake', '0.6.0'
gem 'simplecov', '0.22.0'
gem 'test-unit', '3.6.2'
gem 'timecop', '0.9.8'
gem 'yard', '0.9.36'

install_if -> { RUBY_VERSION >= '2.7' && RUBY_VERSION < '3.0' } do # the ruby version used for linting in the github action
  gem 'syck', require: false
end
