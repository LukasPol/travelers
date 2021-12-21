source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 7.0.0'

gem 'cssbundling-rails', ">= 0.1.0"
gem 'dotenv-rails', '~> 2.5'
gem 'jbuilder', "~> 2.7"
gem 'jsbundling-rails', "~> 0.1.0"
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'redis', '~> 4.0'
gem 'sprockets-rails', ">= 3.4.1"
gem 'stimulus-rails', ">= 0.7.3"
gem 'turbo-rails', ">= 0.9.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]

gem 'bootsnap', require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'factory_bot_rails', '5.2.0'
  gem 'ffaker', '2.12.0'
  gem 'rspec-rails', '~> 4.0.0'
end

group :development do
  gem 'foreman', require: false
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'rubycritic', require: false
  gem 'web-console'
end

group :test do
  gem 'database_cleaner', '1.8.5'
  gem 'shoulda-matchers', '~> 5.0'
  gem 'simplecov', '~> 0.21.2', require: false
end
