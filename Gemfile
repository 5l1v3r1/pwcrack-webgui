source 'https://rubygems.org'

gem "rails", "3.2.6"
gem "mongoid"
gem "bson_ext"
gem "twitter-bootstrap-rails"
gem "mongoid-paperclip", :require => "mongoid_paperclip"
gem "unicorn"
gem "simple_form"
gem "kaminari"
gem "bootstrap-kaminari-views"
gem "delayed_job_mongoid"
# Don't forget to run: rails runner 'Delayed::Backend::Mongoid::Job.create_indexes'

group :development do 
  gem "guard"
  gem "guard-bundler"
  gem "guard-test"
  gem "guard-unicorn"
  gem "pry-rails"
  gem "debugger"
  gem "ruby_gntp" if RUBY_PLATFORM =~ /darwin/
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "sass-rails",   "~> 3.2.3"
  gem "coffee-rails", "~> 3.2.1"

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem "uglifier", ">= 1.0.3"
end

gem "jquery-rails"
