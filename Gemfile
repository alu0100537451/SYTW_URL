source 'https://rubygems.org'

gem 'data_mapper'
gem 'sinatra-contrib'
gem 'haml'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'pry'
gem 'erubis'
gem 'sinatra'


group :production do
	gem 'pg', '~> 0.17.1'
	gem "dm-postgres-adapter"
	gem "sinatra-contrib"
end

group :development, :test do
	gem "sqlite3"
	gem "dm-sqlite-adapter"
end

