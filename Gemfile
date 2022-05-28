source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.3"
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem 'webpacker',  '4.0.7'
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"

gem "bootsnap", require: false
gem "sassc-rails"

group :development, :test do
  gem "sqlite3", "~> 1.4"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem 'listen'
  gem "spring"
  gem 'spring-watcher-listen'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem 'pg', '1.1.4'
end

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]