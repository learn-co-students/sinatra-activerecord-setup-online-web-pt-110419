# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin'
gem 'require_all'
gem 'activerecord', '5.2'	#gives us access to the magical database mapping and association powers
gem 'sinatra-activerecord'	#short for "ruby make", is a package that lets us quickly create files and folders, and automate tasks such as database creation
gem 'rake'					#gives us access to some awesome Rake tasks




group :development do
	gem 'shotgun'
	gem 'pry'
	gem 'tux'					#give us an interactive console that pre-loads our database and ActiveRecord relationships for us
    gem 'sqlite3', '~> 1.3.6'	#is our database adapter gem - it's what allows our Ruby application to communicate with a SQL database. Since we won't use tux and sqlite3 in production, we put them in our :development group - this way, they won't get installed on our server when we deploy our application.

end