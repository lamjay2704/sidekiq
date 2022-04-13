source "https://rubygems.org"

gemspec

gem "rake"
gem "redis-namespace"
gem "rails", "~> 6.1", ">= 6.1.4.4"
gem "sqlite3", platforms: :ruby
gem "activerecord-jdbcsqlite3-adapter", platforms: :jruby

# mail dependencies
gem "net-smtp", platforms: :mri, require: false

group :test do
  gem "minitest"
  gem "simplecov"
  gem "codecov", require: false
end

group :development, :test do
  gem "standard", require: false
  gem "pry"
end

group :load_test do
  gem "hiredis"
  gem "toxiproxy"
end
