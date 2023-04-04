source 'http://rubygems.org'

gem 'rails', '6.1.7.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'awesome_print'
gem 'devise', '>= 4.7.1'
gem 'omniauth', '>= 2.0.0'
gem 'omniauth-oauth2', '>= 1.7.1'
gem 'omniauth-storenvy'
gem 'haml-rails', '>= 1.0.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 2.7.2'
end

gem 'jquery-rails', '>= 4.4.0'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
end

group :development do
  gem 'sqlite3'
  gem 'quiet_assets', '>= 1.0.2'
end

group :production do
  gem 'pg'
  gem 'thin'
end
