source 'https://rubygems.org'

gemspec

group :development do
  gem 'rubocop', '0.40.0'
end

group :test do
  gem 'json'
  gem 'rspec'
  gem 'rack-test'
  gem 'rake'
  gem 'coveralls', require: false
  gem 'rabl'

  platforms :rbx do
    gem 'iconv'
  end
end
