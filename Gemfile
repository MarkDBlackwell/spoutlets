source :rubygems

# Mongoid 3 requires Ruby 1.9.3, per:
# http://mongoid.org/en/mongoid/index.html
ruby '1.9.3'
gem 'bundler', '>=1.3.0.pre.2'
gem 'rake', '10.0.3'
gem 'rails', '3.2.11'

group :assets do
  gem "less-rails", ">= 2.2.6"
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem "twitter-bootstrap-rails", ">= 2.1.8"
end

group :development do
  gem "quiet_assets", ">= 1.0.1"
  gem "better_errors", ">= 0.2.0"
  gem "binding_of_caller", ">= 0.6.8"
end

group :test do
  gem "database_cleaner", ">= 0.9.1"
  gem "mongoid-rspec", ">= 1.5.5"
  gem "email_spec", ">= 1.4.0"
  gem "launchy", ">= 2.1.2"
  gem "capybara", ">= 2.0.1"
end

gem 'jquery-rails'
gem "thin", ">= 1.5.0"
gem "mongoid", ">= 3.0.14"
gem "rspec-rails", ">= 2.11.4", :group => [:development, :test]
gem "cucumber-rails", ">= 1.3.0", :group => :test, :require => false
gem "factory_girl_rails", ">= 4.1.0", :group => [:development, :test]
gem "libv8", ">= 3.11.8"
gem "therubyracer", ">= 0.11.0", :group => :assets, :platform => :ruby, :require => "v8"
gem "omniauth", ">= 1.1.1"
gem "omniauth-facebook"
gem "cancan", ">= 1.6.8"
gem "rolify", ">= 3.2.0"
gem "simple_form", ">= 2.0.4"
gem "figaro", ">= 0.5.0"
