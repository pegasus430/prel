source 'https://rubygems.org'

ruby '2.5.3'

gem 'activeadmin', '1.0.0'
gem 'delayed_job_active_record', '~> 4.1.2'
gem 'devise'
gem 'pg', '0.20.0'
gem 'rails', '~> 4.2'
gem 'unicorn'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 4.2.2'
  gem 'sass-rails',   '~> 5.0.7'
  gem 'uglifier'
end

group :development, :test do
  gem 'pry'
  gem 'rspec-rails', '3.4.2'
  gem 'rspec-mocks', '3.4.1'
  gem 'test-unit', '~> 3.0'
  gem "dotenv-rails"
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

group :production do
  gem 'rails_12factor'
  gem 'rails_serve_static_assets'
end

gem 'puma'

# If you already have a development group, you can add this into it
group :development do
  gem 'capistrano',         require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano3-puma',   require: false
end