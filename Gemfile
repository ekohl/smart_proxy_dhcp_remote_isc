source 'https://rubygems.org'
gemspec

group :development do
  gem 'rake'
  gem 'test-unit'

  if RUBY_VERSION < '2.2.2'
    gem 'rack-test', '~> 0.7.0'
  else
    gem 'rack-test'
  end

  gem 'concurrent-ruby', '~> 1.0', require: 'concurrent'
  gem 'mocha'
  gem 'smart_proxy', :github => 'theforeman/smart-proxy', :branch => 'develop'
end
