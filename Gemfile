source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.3.3'



gem 'rails', '~> 5.1.0'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'devise', '~> 4.3'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'acts_as_votable', '~> 0.10.0'
gem 'simple_form'
gem 'record_tag_helper', '~> 1.0'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13.0'
  gem 'selenium-webdriver'
end

group :development do
  gem 'sqlite3'
  gem 'web-console', '>= 3.3.0'
end

group :production do
  gem 'pg'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'bcrypt', platforms: :ruby
