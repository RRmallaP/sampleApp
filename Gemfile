source 'https://rubygems.org'
ruby '1.9.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.8'

#Use postgresql exclusively
gem 'pg', '0.15.1'

group :development, :test do
	gem 'rspec-rails', '2.13.1'
end

group :test do
	gem 'selenium-webdriver', '2.35.1'
	gem 'capybara', '2.1.0'
	gem 'guard-rspec', '2.5.0'

	gem 'spork-rails', '4.0.0'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.6'
end

# Use SCSS for stylesheets
gem 'sass-rails', '4.0.1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '2.1.1'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '4.0.1'

# Use jquery as the JavaScript library
gem 'jquery-rails', '3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '1.1.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '1.0.2'

group :doc do
	# bundle exec rake doc:rails generates the API under doc/api.
	gem 'sdoc', '0.3.20', require: false
end

group :production do	
	gem 'rails_12factor', '0.0.2'
end

#the following code is added to avoid polling for changes
require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /mswin | mingw | cygwin /i
	gem 'wdm', '>=0.1.0'
end