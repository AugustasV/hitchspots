source "https://rubygems.org"

ruby "2.5.1"

gem "puma"
gem "rake"
gem "sinatra"
gem "sinatra-contrib", require: false

# Mongo DB
gem "bson_ext"
gem "mongo"

# Tools
gem "rollbar"
gem "rubocop"

group :development do
  gem "dotenv"
  gem "rb-fsevent"
  gem "rerun"
end

group :test do
  gem "minitest", "~> 5.0"
  gem "minitest-color"
  gem "rack-test"
  gem "webmock"
end

group :development, :test do
  gem "pry-byebug"
end
