source 'https://rubygems.org'

gem 'rails', '5.0.0.1'

ruby '2.4.0'

# Database
gem 'pg'
gem 'sucker_punch'

# Model
gem 'acts_as_commentable'
gem 'acts-as-taggable-on', github: 'mbleigh/acts-as-taggable-on' # For Rails 5

# Login
gem 'devise'
gem 'omniauth-facebook'

# Assets pipeline
gem 'sass-rails'
gem 'uglifier'
gem 'jquery-rails'
gem 'slim-rails'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'redcarpet'

# Time zone
gem 'tzinfo-data'

# Environment
gem 'dotenv-rails'

# App server
gem 'puma'
gem 'foreman'

#emailing
gem 'premailer-rails'
gem 'nokogiri'

# scraping meetup events
gem 'icalendar'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-rails'
  gem 'spring-commands-rspec'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'faker'
end

group :test do
  gem 'database_cleaner'
  gem 'vcr'
  gem 'webmock'
end

gem 'rails_12factor', group: :production
