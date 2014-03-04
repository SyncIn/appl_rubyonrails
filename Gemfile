source "https://rubygems.org"

# Uncomment this after everyone's moved to Bundler 1.2.0 or later.
# See https://devcenter.heroku.com/articles/ruby-versions
ruby '2.0.0'

gem 'rails', '4.0.1'

# compatibility for rails 3 attr_accessible
# (should be temporary solution)
gem 'protected_attributes'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Web Server and Database
gem 'thin', '1.4.1'
gem 'pg', '0.14.1'

# JavaScript runtime support
gem 'therubyracer'


# Authorization and Authentication
gem 'devise'
gem "cancan", :git => "git://github.com/ryanb/cancan.git", :branch => "2.0"

# API Support
gem 'geocoder', '1.1.3'
gem 'ice_cube'
gem 'twilio-ruby', '3.8.0'
gem 'savon', '2.0.3'
gem 'airbrake', '3.1.4'
gem 'newrelic_rpm'

gem 'sidekiq', '2.3.1'
gem 'sinatra', '1.3.3', require: false
gem 'slim', '1.3.0'

# Statistics
gem 'rack-mini-profiler'
gem 'mixpanel'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails', '2.1.4'
gem 'jquery-ui-rails', '4.0.2'
gem 'bootstrap-sass', github: 'thomas-mcdonald/bootstrap-sass'
gem 'haml', '3.1.7'
gem 'rabl', '0.9.3'
gem 'active_model_serializers'
gem 'i18n-js', :github => 'fnando/i18n-js'
#gem 'i18n-js', '2.1.2'        # Client-side I18n support.

gem 'carrierwave', '0.6.2'
gem 'fog', '~>1.8'            # Support for S3
gem 'carmen-rails', '~> 1.0.0', github: 'jim/carmen-rails' # State/Country lists
gem 'roo', '1.10.1'           # Read-only support for .xls, .xlsx, .ods spreadsheet types

gem 'yaml_db', :git => 'https://github.com/lostapathy/yaml_db.git'
gem 'seed-fu'
gem 'symbolize', '~> 4.4.1'

gem 'sanitize'
gem 'sanitize-rails', :require => 'sanitize/rails'
# TODO (smolnar) tinymce-rails and tinymce-rails-langs causes this error: http://stackoverflow.com/questions/17134769/rails-dont-know-how-to-build-task-assetsprecompileprimary
# gem 'tinymce-rails', '3.5.6'
# gem 'tinymce-rails-langs', '0.1'
gem 'nested_form'
gem 'simple_form'
gem 'wicked', '0.2.0'
gem 'attribute_normalizer', '1.1.0'
gem 'chosen-rails'

# Deploy with Capistrano

gem 'capistrano', '2.14.2'
gem 'capistrano-ext'
gem 'cloudservers', git: 'https://github.com/karnath/ruby-cloudservers'  # rackspace
gem 'foreman'

gem 'whenever', require: false  # cron jobs

gem 'rubyzip', '< 1.0.0'

# To use debugger

group :development do
  # ssh tunneling
  gem 'localtunnel'
  gem 'better_errors'
    gem 'binding_of_caller'

  gem 'guard'
    gem 'rb-inotify', :require => false
    gem 'rb-fsevent', :require => false
    gem 'rb-fchange', :require => false
end


group :development, :test do
  gem 'annotate'
  gem 'debugger'
  gem 'factory_girl_rails'
  gem 'fakeweb'
  gem 'webmock'
  gem 'guard-rspec'
    # guard support
    gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
    gem 'libnotify', require: false
    gem 'rb-inotify'
    gem 'listen'
  gem 'guard-spork'
  gem 'spork-rails'
end

group :development, :test do
  gem 'annotate'
  gem 'debugger'
  gem 'haml-rails'
  gem 'hirb'
  gem 'minitest'
  gem 'ruby-prof'
  gem 'rspec-rails'
  gem 'timecop'
  # Pretty printed test output
  gem 'turn', :require => false
  gem 'webrat'
  gem 'vcr'
end

group :production do
  gem 'unicorn'
end
