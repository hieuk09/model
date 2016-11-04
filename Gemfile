source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 0.8', require: false, github: 'hanami/utils', branch: 'master'

gem 'dry-types', github: 'dry-rb/dry-types', branch: 'master'
gem 'rom-sql',   github: 'jodosha/rom-sql',  branch: 'hanami-model-integration'

platforms :ruby do
  gem 'sqlite3', require: false
  gem 'pg',      require: false
  gem 'mysql2',  require: false
end

platforms :jruby do
  gem 'jdbc-sqlite3',  require: false
  gem 'jdbc-postgres', require: false
  gem 'jdbc-mysql',    require: false
end

gem 'simplecov',          require: false
gem 'coveralls',          require: false
gem 'rubocop', '~> 0.43', require: false
