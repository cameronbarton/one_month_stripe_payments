source 'https://rubygems.org'

# Require a specific ruby version
ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.8'

#Use stripe
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'

# Figaro gem for security managing credentials
gem 'figaro'

# Add letter opener for handling emails in development
gem 'letter_opener', group: :development

# Add activeadmin for admin interface
gem 'activeadmin', github: 'gregbell/active_admin'

# Add devise to support login
gem 'devise'

# Use sqlite3 as the database for Active Record
group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

# Use bootstrap for design
gem 'bootstrap-sass'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
