source "https://rubygems.org"


# Include dependencies from trema.gemspec. DRY!
gemspec

# Add dependencies required to use your gem here.
gem 'phuture', :github => 'trema/phuture', :branch => 'feature/phut_run'

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem 'aruba', '~> 0.5.3'
  gem 'cucumber', '~> 1.3.8'
  gem 'flay', '~> 2.4.0'
  gem 'flog', '~> 4.2.0'
  gem 'fuubar', '~> 1.2.1'
  gem 'guard', '~> 1.8.3' if RUBY_VERSION < '1.9.0'
  gem 'guard', '~> 2.2.3' if RUBY_VERSION >= '1.9.0'
  gem 'guard-bundler', '~> 1.0.0' if RUBY_VERSION < '1.9.0'
  gem 'guard-bundler', '~> 2.0.0' if RUBY_VERSION >= '1.9.0'
  gem 'guard-cucumber', '~> 1.4.0'
  gem 'guard-rspec', '~> 3.1.0' if RUBY_VERSION < '1.9.0'
  gem 'guard-rspec', '~> 4.0.3' if RUBY_VERSION >= '1.9.0'
  gem 'mime-types', '~> 1.25' if RUBY_VERSION < '1.9.0'
  gem 'mime-types', '~> 2.0' if RUBY_VERSION >= '1.9.0'
  gem 'rcov', '~> 1.0.0' if RUBY_VERSION < '1.9.0'
  gem 'redcarpet', '~> 2.3.0' if RUBY_VERSION < '1.9.0'
  gem 'redcarpet', '~> 3.0.0' if RUBY_VERSION >= '1.9.0'
  gem 'reek', '~> 1.3.4'
  gem 'relish', '~> 0.7'
  gem 'rspec', '~> 2.14.1'
  gem 'yard', '~> 0.8.7.2'
end


### Local variables:
### mode: Ruby
### coding: utf-8-unix
### indent-tabs-mode: nil
### End:
