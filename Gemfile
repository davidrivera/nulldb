source "https://rubygems.org"

gem 'activerecord', '>= 2.0.0'

platforms :ruby_20, :ruby_21 do
  gem 'iconv'
  gem 'coveralls', :group => :test, :require => false
end

group :development, :test do
  gem 'spec'
  gem 'rspec', '>= 1.2.9'
  gem 'rake'
end

group :development do
  gem 'jeweler'
  gem 'appraisal', :github => 'thoughtbot/appraisal'
end
