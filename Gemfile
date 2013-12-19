source 'http://ruby.taobao.org'
gem "rails", "~> 4.0.0"
platforms :ruby, :mingw do
  # use mysql
  gem 'mysql2'
  # use sqlite3
  gem 'sqlite3'
end

platforms :jruby do
  gem 'jruby-openssl'
  gem 'activerecord-jdbcmysql-adapter', :require => false
  # use sqlite3
  gem 'activerecord-jdbcsqlite3-adapter', :require => false
  #gem 'jruby-ehcache', :require => 'ehcache'
  #gem 'trinidad', :require => false, :groups => 'production'
  gem 'warbler'
end

gem 'puma', :platforms => [:jruby, :ruby]
gem 'rails-observers'
gem 'protected_attributes'
gem 'will_paginate'
gem "aasm"
gem 'paperclip'
gem 'compass'
gem 'dalli'
gem "oauth"
gem "oauth-plugin"
gem 'delayed_job'
gem 'delayed_job_active_record'
#gem "delayed_job_web"
gem 'super_cache'
gem 'rufus-scheduler'
gem 'acts_as_list'
gem 'awesome_nested_set'
gem 'themes_for_rails', github: 'tkriplean/themes_for_rails'
gem 'inherited_resources'
gem 'squeel'
gem 'mobile-fu'
gem "calendar_helper"
#gem "rinku", :require => 'rails_rinku', :platforms
gem 'rails_autolink'
gem 'acts_as_favorite', :git => 'https://github.com/ShiningRay/acts_as_favorite.git'
gem 'acts_as_taggable_on_steroids', :git => 'https://github.com/ShiningRay/acts_as_taggable_on_steroids.git', :require => 'acts_as_taggable'
gem 'alias_fallback', :git => 'https://github.com/ShiningRay/alias_fallback.git'
gem "rolify", '~> 3.1'
gem 'dynamic_form'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'therubyrhino', :platforms => :jruby
  gem 'uglifier', '>= 1.0.3'
  #gem 'turbo-sprockets-rails3'
end

group :development do
  gem 'capistrano'
  gem 'win32console', '~> 1.3.2', :platforms => :mingw
  gem 'jruby-pageant', :require => false, :platforms => :jruby
end

group :test, :development do
  gem "rspec-rails", "~> 2.0"
  gem 'guard-livereload'
  gem 'guard-cucumber'
  gem 'guard-bundler'
  gem 'rack-livereload'
  gem 'guard-jruby-rspec', :platforms => :jruby
end

group :test do
  gem "factory_girl_rails"
  gem 'guard'
  gem 'guard-rspec'
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', '~> 0.9.1', :require => false
  gem 'rb-fchange', :require => false
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'ruby_gntp'
  gem 'quiet_assets'
  gem 'forgery'
  gem 'cucumber-rails', :require => false
end

group :production do
  gem 'rack-cache'
end

