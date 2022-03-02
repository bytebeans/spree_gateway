source 'https://rubygems.org'

gem 'rails-controller-testing'
gem 'spree', github: 'bytebeans/spree', branch: 'bytebeans'
gem 'spree_backend', github: 'bytebeans/spree', branch: 'bytebeans'
gem 'spree_frontend', github: 'bytebeans/spree', branch: 'bytebeans'

if ENV['DB'] == 'mysql'
  gem 'mysql2'
else
  gem 'pg', '~> 1.1'
end

gemspec
