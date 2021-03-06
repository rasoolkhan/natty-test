source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.1.2'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

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
gem 'aws-sdk-rails', '~> 1.0'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :production do
  gem 'unicorn'
  gem 'mysql2', '~> 0.3.18'
end

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'sqlite3'
  gem 'autotest-rails'
  gem 'capybara'
  gem 'shoulda'
end

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'spree', :github => 'spree/spree', :branch => '2-3-stable'
gem 'spree_gateway', github: 'spree/spree_gateway', branch: '2-1-stable'
gem 'spree_auth_devise', github: 'spree/spree_auth_devise', branch: '2-1-stable'
gem 'spree_drop_ship', github: 'spree-contrib/spree_drop_ship',  branch: '2-1-stable'
gem 'spree_static_content', github: 'spree-contrib/spree_static_content', branch: '2-1-stable'
gem 'spree_social', github: 'spree-contrib/spree_social', branch: '2-1-stable'
gem 'spree_product_preview', github: 'freego/spree_product_preview', branch: '2-1-stable'
gem 'spree_banner', '~> 2.0.0', github: 'dbwinger/spree_banner'
gem 'spree_digital', github: 'halo/spree_digital', branch: '2-1-stable'
