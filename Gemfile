source 'https://rubygems.org'
ruby '1.9.3'

gem 'json'
gem 'locomotive_cms', '~> 2.0.0.rc12', :require => 'locomotive/engine'
gem 'locomotive-heroku', '~> 0.0.2', :require => 'locomotive/heroku'
gem 'rails', '3.2.8'

group :production do
  gem 'thin'
end

group :assets do
  gem 'coffee-rails',   '~> 3.2.2'
  gem 'compass-rails',  '~> 1.0.2'
  gem 'sass-rails',     '~> 3.2.4'
  gem 'uglifier',       '~> 1.2.4'
end

group :development do
  gem 'unicorn'
end
