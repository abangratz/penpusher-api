source 'https://rubygems.org'

gem 'rails', '3.2.11'

gem 'rails-api'

gem 'unicorn'
gem 'capistrano', group: :development

gem 'pg'
gem 'sequel-rails', git: 'https://github.com/TalentBox/sequel-rails'

group :development, :test do
  gem 'rspec-rails', git: 'https://github.com/rspec/rspec-rails'
  gem 'capybara'
  gem 'pry-rails'
end

group :test do
  gem 'cucumber-rails', git: 'https://github.com/cucumber/cucumber-rails.git'
  gem 'database_cleaner'
end
