source 'http://rubygems.org'

gem 'rails', '5.2.4.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'awesome_print'
gem 'devise'
gem 'omniauth'
gem 'omniauth-oauth2'
gem 'omniauth-storenvy'
gem 'haml-rails', '>= 0.5.3'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.5'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails', '>= 4.0.1'

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
