ENV['MOPED_VERSION'] = 'skip'
ENV['MONGOID_VERSION'] = 'skip'
ENV['TILT_VERSION'] = '~> 2.0'

eval_gemfile File.expand_path('../gemfiles/Gemfile.base', __FILE__)

gem 'rails', ">= 5.0.2"
gem 'sinatra', "2.0.0.rc1"

group :development do
  gem 'yard'
  gem 'pry'
  gem 'pry-byebug'
end

