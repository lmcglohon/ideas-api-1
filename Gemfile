source 'https://rubygems.org'

ruby '2.6.3'

gem 'rails', '~> 6.0.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'rack-cors'
gem 'jsonapi-resources'
gem 'bcrypt'
gem 'doorkeeper'
gem 'dotenv-rails'

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'bullet'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'coderay'
  gem 'rubocop'
end

group :test do
  gem 'factory_bot_rails'
  gem 'rspec_junit_formatter'
end

group :production do
  gem 'rack-attack'
end
