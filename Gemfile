source 'https://rubygems.org'

gem 'rails'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'sqlite3'
gem 'pg'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
    # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier'
end

gem 'jquery-rails'

gem 'haml'
gem 'haml-rails'
gem 'less-rails' #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails'

gem 'sorcery'
gem 'paperclip'
gem 'kaminari'
gem 'paper_trail'

gem 'i18n'
gem 'russian'
gem 'bcrypt-ruby'

gem 'sunspot_rails' #форк для rails
gem 'sunspot_solr'  #сам Solr
gem 'progress_bar'  #нужен для индексирования
group :test, :development do #в группу для разработки и тестирования
  gem 'sunspot-rails-tester' #это нужно для запуска тестов, иначе не работает.                            #...
end
