source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.0'
gem 'carrierwave'
gem 'mini_magick'
gem 'devise'
gem 'therubyracer'
gem 'ckeditor', '~> 4.1'
gem 'simple_form', '~> 3.2'
gem 'bootstrap-sass', '~> 3.3'
gem 'rails', '~> 5.0.3'
gem 'puma'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem "font-awesome-rails" # Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'
gem 'mail_form', '~>1.7.0'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg', '~> 0.20.0'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
