source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '~> 4.0.0'
# gem 'sqlite3' # Use sqlite (>= 3.6.16) as the database
gem 'mysql2' # Use myql as the database
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0' # compressor for JavaScript assets
gem 'therubyracer', platforms: :ruby # Embeded V8 Javascript Interpreter (required for sprockets, asset pipeline)
gem 'jquery-rails'
gem 'jquery-ui-rails'
# gem 'turbolinks'
# gem 'jquery-turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'unicorn'

gem 'slim', :require => 'slim-rails'
gem "slim-rails"
gem 'twitter-bootstrap-rails'
gem 'bootstrap-sass' # http://d.hatena.ne.jp/sandmark/20120321/1332292995
gem 'bootswatch-rails'
gem 'bootstrap-datetimepicker-rails'
gem 'font-awesome-rails' # Font-Awesome web fonts

group :development do
  gem 'yard' # document genration
  gem 'better_errors' # sophisticated error view
  gem 'binding_of_caller' # add irb/pry on better_rails view
  gem 'bullet' # warn N+1 queries
  gem 'rack-mini-profiler' # simple profiler
  # gem 'newrelic_rpm' # use newrelic as a performance profiler
end

group :development, :test do
  gem 'spring' # rails application preloader
  gem 'guard'
  gem 'rspec-rails' # rails g rspec:model
  gem 'guard-rspec' # automatically run specs
  gem 'byebug' # ruby 2.0 debugger
  gem 'pry'
  gem 'pry-byebug'
end  
