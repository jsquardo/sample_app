source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.2"

gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.1"
gem "rails", "~> 6.0.3", ">= 6.0.3.4"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"
gem "jbuilder", "2.9.1"
gem "bootsnap", ">= 1.4.2", require: false
gem "htmlbeautifier"
gem "rufo"

group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem "listen", "~> 3.2"
  gem "web-console", ">= 3.3.0"
  gem "spring", "2.1.0"
  gem "spring-watcher-listen", "2.0.1"
end

group :test do
  gem "capybara", "3.32.2"
  gem "selenium-webdriver", "3.142.7"
  gem "webdrivers", "4.3.0"
  gem "rails-controller-testing", "1.0.4"
  gem "minitest", "5.11.3"
  gem "minitest-reporters", "1.3.8"
  gem "guard", "2.16.2"
  gem "guard-minitest", "2.4.6"
end

gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

gem "rspec-rails", "~> 4.0", :groups => %i[development test]

gem "redis", "~> 4.2"

gem "image_processing", "~> 1.12"

gem "dotenv-rails", "~> 2.7", :groups => %i[development test]

gem "rubocop", "~> 1.1", :group => :development

gem "rubocop-rails", "~> 2.8", :group => :development

gem "letter_opener", "~> 1.7", :group => :development

gem "letter_opener_web", "~> 1.4", :group => :development

gem "lograge", "~> 0.11.2"

gem "sentry-raven", "~> 3.1"

gem "barnes", "~> 0.0.8"

gem "sidekiq", "~> 6.1"

gem "sidekiq-cron", "~> 1.2"
