source 'https://rubygems.org'

ruby "2.1.5"

gem 'rails', '4.1.8'  #no squiggly meand is must be this exact version
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0' #squiggly line means it can upgrade to 2.x but not 3.0
gem 'bootstrap-sass'
gem 'devise'

group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem "rails_12factor"
end


group :doc do 
	#bundle exec rake doc:rails generates the API under doc/api.
	gem 'sdoc', '~> 0.4.0',          group: :doc
	gem 'tzinfo-data', platforms: [:mingw, :mswin]
end