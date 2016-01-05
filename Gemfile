source 'https://rubygems.org'
ruby '2.1.5'

group :development do
  gem 'emeril', '~> 0.8.0'
  gem 'guard', '~> 2.13.0'
  gem 'guard-foodcritic', '~> 2.0.0'
  gem 'guard-rspec', '~> 4.6.4'
  gem 'guard-rubocop', '~> 1.2.0'
end

group :test do
  # gem 'berkshelf', '~> 4.0.1'
  gem 'chefspec', '~> 4.4.0'
  gem 'coveralls', '~> 0.8.3', require: false
  gem 'foodcritic', '~> 5.0.0'
  gem 'json_spec', '~> 1.1.4'
  gem 'rake', '>= 10.2'
  gem 'rubocop', '= 0.34.2'
end

group :integration do
  gem 'kitchen-docker', '~> 2.3.0'
  gem 'kitchen-vagrant', '~> 0.19.0'
  gem 'test-kitchen', '~> 1.4.2'
  gem 'travis-lint'
  gem 'serverspec'
  gem 'winrm-transport'
end

# gem install bundler -v 1.7.15
gem 'builderator', '~> 0.0'

gem 'vagrant', :github => 'mitchellh/vagrant',
               :tag => 'v1.7.4',
               :group => :development

group :plugins do
  gem 'vagrant-aws'
  gem 'vagrant-omnibus'
  gem 'vagrant-secret'
end
