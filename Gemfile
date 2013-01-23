source 'http://rubygems.org'

gem 'pry'
gem "rspec-rails", "~> 2.12.2", :group => [:test, :development]
#gem "rspec-rails", :group => [:test, :development]

group :test do
  gem 'ffaker'
  # gem 'spree_auth', '~> 1.0.0'
  # gem "spree_auth_devise", "~> 1.3.1"
  gem 'spree_auth_devise', :git => "git://github.com/spree/spree_auth_devise"
  gem 'devise-encryptable'
  gem 'spree_gateway',
    :github => 'spree/spree_gateway',
    :branch => '1-3-stable'
  gem 'database_cleaner'
  gem 'factory_girl_rails', '~> 1.7.0'
  #gem "factory_girl_rails"
  gem "capybara", '1.1.3'
  gem "guard-rspec"
  gem 'launchy'
end

if RUBY_VERSION < "1.9"
  gem "ruby-debug"
else
  gem "ruby-debug19"
end

gem 'spree', '~> 1.3.0'

gemspec
