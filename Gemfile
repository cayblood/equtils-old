source :rubygems

# deployment requirements
gem 'heroku'
group :production do
  gem 'bundler'
  gem 'do_postgres'
  gem 'dm-postgres-adapter'
  gem 'pg'
end

# Server requirements (defaults to WEBrick)
# gem 'thin'
# gem 'mongrel'

# Project requirements
gem 'rake'
gem 'sinatra'
gem 'sinatra-flash', :require => 'sinatra/flash'

# Component requirements
gem 'bcrypt-ruby', :require => "bcrypt"
gem 'haml'
gem 'dm-sqlite-adapter'
gem 'dm-validations'
gem 'dm-timestamps'
gem 'dm-migrations'
gem 'dm-constraints'
gem 'dm-aggregates'
gem 'dm-core'

# Test requirements

# Padrino Stable Gem
gem 'padrino', '0.10.5'

# Or Padrino Edge
# gem 'padrino', :git => 'git://github.com/padrino/padrino-framework.git'

# Or Individual Gems
# %w(core gen helpers cache mailer admin).each do |g|
#   gem 'padrino-' + g, '0.10.5'
# end
