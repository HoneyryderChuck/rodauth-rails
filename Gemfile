source "https://rubygems.org"

gemspec

gem "rake", "~> 13.0"
gem "warning"

gem "rails", ">= 4.2"
gem "sqlite3", "~> 1.3",                platforms: :mri
gem "activerecord-jdbcsqlite3-adapter", platforms: :jruby

gem "capybara"

if RUBY_VERSION >= "3.1.0"
  # mail gem dependencies on Ruby 3.1+
  gem "net-smtp"
  gem "net-imap"
  gem "net-pop"

  # rake gem dependency on Ruby 3.1+
  gem "matrix"
end
