source :rubygems

gem 'sinatra'
gem 'twitter'
gem 'heroku'
gem 'haml'
gem 'rake'

group :test do
  gem 'guard'
  gem 'guard-rspec'
  gem 'rspec'
  gem 'rack-test'
end

group :development do
	if RUBY_PLATFORM.downcase.include?("darwin")
		gem 'growl_notify'
	end
end

