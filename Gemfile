source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.7', '>= 5.0.7.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.3.13'
# Added Postgres support
gem 'pg', '~> 0.18.4'
# In order to use UUID as ids
gem 'ar-uuid', '~> 0.1.2'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

# Active Model Serializer
gem 'active_model_serializers', '~> 0.10.4'
# Configure environment with dotenv files
gem 'dotenv-rails', '~> 2.2', '>= 2.2.0'
# Datadog APM
gem 'ddtrace', '~> 0.4.0', require: false
# AASM State machines
gem 'aasm', '~> 5.0.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 9.0.6', platform: :mri
  gem 'webmock', '~> 2.3.2', platform: :mri
  gem 'simplecov', '~> 0.12.0'
  gem 'simplecov-cobertura', '~> 1.0', '>= 1.0.2'
end

group :development do
  gem 'listen', '~> 3.0.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0.1'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2.2', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# For storing the results in S3
gem 'aws-sdk-rails', '~> 1.0.1'

# json chunk parser
gem 'json-stream', '~> 0.2.1'

# manage views from migrations
gem 'scenic', '~> 1.4.1'