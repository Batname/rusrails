source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', " ~> 4.0.0"
gem 'russian'
gem 'static_docs' #, path: "/Users/mikdiet/projects/opensource/static_docs"


group :production do
  gem 'pg'
end

gem 'textacular', '~> 3.0'


gem 'sqlite3'

gem 'nokogiri'
gem 'sass-rails', '~> 4.0.0'
gem "less-rails"
gem 'haml-rails'
gem 'RedCloth'
gem 'redcarpet'
gem 'rails_config'
gem 'twitter-bootstrap-rails'
gem 'jquery-rails'

gem 'capistrano', '~> 2.15'
gem 'therubyracer'
gem 'unicorn'

gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'

group :development do
  gem 'quiet_assets'
  # Need for cap tasks for 3.2 branch
  gem 'thinking-sphinx', require: false
end

group :development, :test do
  gem "rspec-rails"
  gem 'webrat'
  gem 'pry-rails'
end

group :test do
  gem 'factory_girl_rails'
  gem 'database_cleaner'
end
