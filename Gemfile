source 'https://rubygems.org'

ruby '3.0.2'

group :test do
  gem 'rspec'
  gem 'simplecov', require: false, group: :test
  gem 'simplecov-console', require: false, group: :test
  gem 'timecop'
  gem 'twilio_mock'
end

group :development, :test do
  gem 'rubocop', '1.20'
end

gem 'twilio-ruby', '~> 5.66.2'
gem 'rack'
gem 'dotenv'
