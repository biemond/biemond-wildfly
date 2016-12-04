source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? "= #{ENV['PUPPET_VERSION']}" : ['= 4.2.3']

gem 'coveralls', :require => false
gem 'simplecov', :require => false
gem 'simplecov-console'
gem 'puppet-lint'
gem 'puppet', puppetversion
gem 'rspec', '>= 3.2.0'
gem 'rspec-puppet', '>= 2.1.0'
gem 'rspec-system-puppet'
gem 'puppetlabs_spec_helper'
gem 'puppet-syntax'
gem 'facter', '>= 1.6.10'
gem 'rubocop', require: false
gem 'rubocop-rspec', '1.5.0'
gem 'puppet-blacksmith'
gem 'treetop'
gem 'net-http-digest_auth'
gem 'metadata-json-lint', '>= 0.0.11'
gem 'google-api-client', '>= 0.9'
gem 'activesupport', '4.2.7.1'

group :acceptance do
  gem 'fog', '>= 1.25.0'
  gem 'beaker', '3.5.0'
  gem 'beaker-puppet_install_helper'
  gem 'beaker-rspec'
  gem 'serverspec', '>= 2.0.0'
end
