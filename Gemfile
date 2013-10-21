source 'https://rubygems.org'

ruby '1.9.3' # Ruby version
gem 'rails', '3.2.13' #Rails version


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'
end


gem 'jquery-rails' #jQuery
gem 'devise' # User authentication

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '~>2.4' # framework for unit testing
end

group :test do
  gem 'database_cleaner' # reset your db to a pristine state during testing
end


group :production do 
  gem 'thin'  # heroku web server
  gem 'pg'  # postgres db gem
  
  # MemCachier, Dalli for cache
  gem 'memcachier'
  gem 'dalli'

end