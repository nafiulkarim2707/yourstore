source 'http://rubygems.org'

gem 'rails'

gem 'jquery-rails'
gem 'nokogiri'
gem 'mechanize'
gem 'devise'
gem 'cancan'
gem 'default_value_for'
gem 'inherited_resources'
gem 'haml'
gem 'sass'
gem 'mysql2'
gem 'whenever', :require => false
gem 'acts-as-taggable-on', '~> 2.2.2'

gem 'sunspot_rails'
gem 'sunspot_solr'

gem 'rmagick'
gem 'spree'
gem 'spree_cmd'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'rails-erd'
  gem 'growl'
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'progress_bar'
end

group :ci, :test, :development, :staging, :qa do
  gem 'rspec-rails'
  gem 'launchy'
  gem 'rspec-core'
  gem 'rspec2-rails-views-matchers'
  gem 'capistrano'
  gem 'capistrano-ext'
  gem 'rvm'
  gem 'spork'
  gem 'watchr'
  gem 'ruby-debug19'
  gem 'turn', '~> 0.8.3', :require => false
  gem 'factory_girl_rails'
end

group :test do
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'webmock'
end
gem 'spree_usa_epay', :git => 'https://github.com/spree/spree_usa_epay'
gem 'spree_skrill'

