source "https://rubygems.org"
ruby "2.1.2"

gem "honeybadger"
gem "multi_json"
gem "oj"
gem "pliny", github: "morhekil/pliny"
gem "puma"
gem "rack-ssl"
gem "rake"
gem "sinatra", require: "sinatra/base"
gem "sinatra-contrib", require: ["sinatra/namespace", "sinatra/reloader"]
gem "sinatra-router"

group :development do
  gem "foreman"
end

group :test do
  gem "committee"
  gem "rack-test"
  gem "rr", require: false
  gem "rspec-core"
  gem "rspec-expectations"
end
