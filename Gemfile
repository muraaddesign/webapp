source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.2'

# User authentication
gem 'devise'
gem 'devise_invitable'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'
gem 'omnicontacts'
gem 'google-api-client'
gem 'google_contacts_api'
gem 'fb_graph2'
gem 'koala', '~> 2.2'

# OAuth2 server
gem 'doorkeeper'
gem "doorkeeper-grants_assertion", github: "Inittec/doorkeeper-grants_assertion", branch: "master"

# API development
gem 'grape', '~> 0.16.2'
gem 'grape-entity'
gem 'grape-doorkeeper'
gem 'grape-active_model_serializers'
gem 'hashie-forbidden_attributes'
gem 'grape-scaffold'
gem 'grape-swagger', '~> 0.20.2'
gem 'grape-swagger-rails',  '~> 0.2.1'

gem 'rack-cors', :require => 'rack/cors'

gem 'pg'

gem 'dotenv-rails'

gem "paperclip", "~> 5.0.0"

gem 'pry-rails'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'annotate'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'letter_opener'

gem 'aws-sdk', '~> 2'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
