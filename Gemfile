source "https://rubygems.org"

gem "rails", "~> 6.1.0"
gem "rails-i18n"

gem "aws-sdk-s3"
gem "aws-sdk-sqs"
gem "bootsnap"
gem "clearance"
gem "dalli"
gem "delayed_job"
gem "delayed_job_active_record"
gem "gravtastic"
gem "high_voltage"
gem "honeybadger"
gem "http_accept_language"
gem "jquery-rails"
gem "kaminari"
gem "mail"
gem "newrelic_rpm"
gem "pg"
gem "rack"
gem "rack-utf8_sanitizer"
gem "rbtrace", "~> 0.4.8"
gem "rdoc"
gem "rest-client", require: "rest_client"
gem "roadie-rails"
gem "shoryuken", "~> 4.0", require: false
gem "statsd-instrument", "~> 2.3.0"
gem "unicorn", "~> 5.8.0"
gem "validates_formatting_of"
gem "elasticsearch-model", "~> 7.0"
gem "elasticsearch-rails", "~> 7.0"
gem "elasticsearch-dsl", "~> 0.1.2"
gem "faraday_middleware-aws-sigv4", "~> 0.3"
gem "xml-simple"
gem "compact_index", "~> 0.13.0"
gem "sprockets-rails"
gem "rack-attack"
gem "rqrcode"
gem "rotp"
gem "unpwn"

# Logging
gem "lograge"

group :assets do
  gem "sassc-rails"
  gem "uglifier", ">= 1.0.3"
  gem "autoprefixer-rails"
end

group :development, :test do
  gem "m", "~> 1.5", require: false
  gem "pry-byebug"
  gem "toxiproxy", "~> 1.0.0"
  gem "webrick"

  gem "brakeman", require: false
  gem "rubocop", "0.93.1", require: false
  gem "rubocop-rails", "2.9.1", require: false
  gem "rubocop-performance", "1.10.2", require: false
end

group :development do
  gem "rails-erd"
  gem "listen"
end

group :test do
  gem "minitest", require: false
  gem "capybara", "~> 3.35"
  gem "factory_bot_rails"
  gem "launchy"
  gem "rack-test", require: "rack/test"
  gem "mocha", require: false
  gem "shoulda"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "simplecov", require: false
end
