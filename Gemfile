source "http://rubygems.org"

gem "activerecord", :require => "active_record"
gem "appraisal"
gem "aws-s3", :require => "aws/s3"
gem "bundler"
gem "cocaine"
gem "fog"
gem "mime-types"
gem "mocha"
gem "rake"
gem "rdoc", :require => false
gem "shoulda"
if defined?(JRUBY_VERSION)
  gem "jruby-openssl"
  gem 'activerecord-jdbc-adapter'
  gem 'jdbc-sqlite3'
else
  gem "sqlite3", "~>1.3.4"
end

# This is for Rails 3.1
gem "sprockets", "~> 2.0.0.beta.13", :require => false

# gem "ruby-debug", :platform => :ruby_18
# gem "ruby-debug19", :platform => :ruby_19
