source 'https://rubygems.org'
gem "rails", "~> 4.2.0"

gem "mysql2", "~> 0.3.18"

gem "bourbon", "~> 3.2.3"
gem "coffee-rails"
gem "neat", "~> 1.6.0"
gem "sass-rails"
gem "uglifier", ">= 1.3.0"
gem "yui-compressor", "~> 0.12.0"

gem "bootstrap-datepicker-rails", "~> 1.1.1.10"
gem "bootstrap-sass", "3.1.1.0"
gem "chartkick", "~> 1.2.1"
gem "chosen-rails"
gem "jquery-easing-rails"
gem "jquery-rails"
gem "jquery-tokeninput-rails", "~> 1.6.0"
gem "jquery-ui-rails", "~> 4.1.0"
gem "unicorn", "4.6.3"
gem "unicorn-worker-killer"
gem "webpacker"

# After upgrading to Rails 6, this gem can be removed and configure the SameSite
# policy via config/initializers/cookie.rb
gem "rails_same_site_cookie"

gem "rails-observers"

gem "acts_as_list"
gem "ancestry", "2.0.0"
gem "browser", "~> 0.7.0"
gem "cancancan", "~> 1.6"
gem "carrierwave", "~> 1.0.0"
gem "carrierwave_backgrounder",
    # As of 5/4/2017 carrierwave_backgrounder is broken with carrierwave 1.x
    # This commit includes a fix for missing cache_name method
    github: "ajjahn/carrierwave_backgrounder",
    ref: "011453867f66760d90558432f795e20766097262"
gem "kaminari", "~> 0.17.0"
gem "mini_magick"
gem "money", "~> 5.0.0"
gem "newrelic_rpm"
gem "nokogiri" # , "~> 1.6.0"
gem "ranked-model", "~> 0.3"
gem "redis"
gem "redis-namespace"
gem "rubyzip", "~> 0.9.1", require: "zip/zip"
gem "sidekiq", "~> 4.0", require: "sidekiq/web"
gem "sidekiq-limit_fetch"
gem "sidekiq-middleware"
gem "sinatra", ">= 1.3.0", require: nil
gem "unf", "~> 0.1.3"

gem "active_link_to", "~> 1.0.1"
gem "crypt", "~> 1.1.4"
gem "dispatch_js", github: "vectorjohn/dispatch_js", branch: "main"
gem "geoip", "~> 0.8.9"
gem "rdiscount", "~> 2.1.7"

gem "roadie-rails"
gem "slim"
gem "state_machine", "1.2.0"
gem "valid_email", require: "valid_email/email_validator"

gem "devise", "4.4.3"
gem "rack-oauth2"
gem "responders"

gem "carmen"
gem "geocoder"

gem "dynamic_form", "~> 1.1.4"
gem "RedCloth", "~> 4.2.9"

gem "friendly_id", "~> 5.0.0"
gem "ransack"

gem "cityhash", "~> 0.8.1"
gem "dalli", "~> 2.6.4"
gem "figaro", "~> 0.7.0"
gem "identity_cache"
gem "simple_form"

gem "parallel"
gem "progress_bar"
gem "ruby-progressbar"
gem "sunspot_rails", "2.2.0"
gem "sunspot_solr", "2.2.0"

gem "whenever", "~> 0.9.0", require: false

gem "active_model_serializers", "~> 0.8.1"

gem "counter_culture"
gem "enumerize", "~> 1.0.0"
gem "recommendable", github: "davidcelis/recommendable",
                     ref: "d78e6f7192265d578b89b571aac7bafef8cb4c56"
gem "uuid"

gem "active_model-errors_details"
gem "fog-aws"
gem "fog-local"
gem "hashid-rails", "~> 1.0"
gem "jwt", "~> 2.1"
gem "pdf-reader"
gem "pdfkit"
gem "wkhtmltopdf-binary"

# Why do we need this gem?
gem "httparty"

group :development do
  gem "letter_opener"
  gem "traceroute"
end

group :development, :test do
  gem "awesome_print"
  gem "faker"
  gem "guard-rspec"
  gem "pry-byebug"
  gem "site_prism"
end

group :test do
  gem "apparition"
  gem "capybara"
  gem "celluloid-io"
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "puma"
  gem "rspec-rails"
  gem "shoulda", require: false
  gem "shoulda-matchers", require: false
  gem "timecop"
  gem "vcr"
  gem "webmock"

  gem "apivore"
  gem "launchy"
  gem "sunspot_matchers"
  gem "sunspot_test", github: "collectiveidea/sunspot_test",
                      ref: "abae5bf827d6d021aa7df5a3911f517b577974a5"
end
