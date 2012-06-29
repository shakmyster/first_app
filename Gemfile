source 'https://rubygems.org'

gem 'rails', '3.2.6'
group :production, :staging do
  gem "pg"
end

group :development, :test do
  gem "sqlite3-ruby", "~> 1.3.0", :require => "sqlite3"
end