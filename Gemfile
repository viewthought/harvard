source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'jquery-rails', '2.2.0'
gem 'haml-rails'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'

  # Compass specific gems.
  gem 'compass-rails'
  gem 'oily_png'
  gem 'susy'
  gem 'fancy-buttons'
end

# See https://github.com/ndbroadbent/turbo-sprockets-rails3
# gem 'turbo-sprockets-rails3'

group :test do
  gem 'capybara', '1.1.2'
end

group :production do
  gem 'pg', '0.12.2'
end

gem 'spree', '1.3.2'
gem 'spree_gateway', :github => 'spree/spree_gateway', :branch => '1-3-stable'
gem 'spree_auth_devise', :github => 'spree/spree_auth_devise', :branch => '1-3-stable'
gem 'spree_static_content', :git => 'git://github.com/spree/spree_static_content.git', :branch => '1-3-stable'
gem 'spree_paypal_express', :git => 'git://github.com/spree/spree_paypal_express.git', :branch => '1-3-stable'
