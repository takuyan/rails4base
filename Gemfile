source 'https://rubygems.org'
ruby '2.1.2'

# Framework
gem 'rails', '4.1.4'

# Database
gem 'pg'

# Authentication
gem 'devise'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-github'
gem 'omniauth-facebook'

# APIs
gem 'bugsnag'

# Assets
gem 'jbuilder', '~> 2.0'
gem 'sass-rails',   '~> 4.0'
gem 'coffee-rails', '~> 4.0'
gem 'uglifier', '>= 1.3.0'
gem 'haml-rails'

# Helpers
gem 'active_decorator'

# Models
gem 'figaro'
gem 'enumerize'
gem 'validates_email_format_of'
gem 'unf'
gem 'fog'
gem 'mini_magick'

# Views
gem 'bootstrap-sass'
gem 'compass-rails'
gem 'font-awesome-rails'
gem 'jquery-rails'
gem 'simple_form'
gem 'kaminari'

# Server
gem 'puma'
gem 'rack-rewrite'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :development do
  # Debugs
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'hirb'
  gem 'hirb-unicode'
  gem 'letter_opener'
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'quiet_assets'
  gem 'tapp'
  gem 'view_source_map'
  gem 'i18n-tasks'
  gem 'thin'
end

group :test, :development do
  # TDD
  gem 'brakeman'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'delorean'
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'guard-rspec', require: false
  gem 'guard-sprockets2'
  gem 'json_expressions'
  gem 'launchy'
  gem 'poltergeist'
  gem 'rails-db-resetup'
  gem 'rb-fsevent', require: RUBY_PLATFORM.downcase =~ /darwin/ ? 'rb-fsevent' : false
  gem 'rspec', '~> 3.0'
  gem 'rspec-rails'
  gem 'minitest'
  gem 'shoulda-matchers', '2.5.0'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'json_spec'
end

group :production, :staging do
  gem 'rails_12factor'
  gem 'newrelic_rpm'
end
