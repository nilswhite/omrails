source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.12'
gem 'jquery-rails'
gem 'devise'

group :production do
	gem 'pg'
	gem 'unicorn'
end

group :development, :test do
	gem 'sqlite3'
	gem 'webrick'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', '~> 2.3.2.1'
end

