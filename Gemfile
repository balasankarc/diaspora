source "https://rubygems.org"

gem "rails", "~> 4.2.5"

# Legacy Rails features, remove me!
# responders (class level)
gem "responders", "~> 2.1"

# Appserver

gem "unicorn", ">= 4.9", require: false

# Federation

gem "diaspora_federation-rails", "0.0.13"

# API and JSON

gem "acts_as_api", "~> 0.4.2"
gem "json",        "~> 1.8", ">= 1.8.3"
gem "json-schema", "~> 2.6"

# Authentication

gem "devise", "~> 4.0"
gem "devise_lastseenable", "~> 0.0.6"
gem "devise-token_authenticatable", "~> 0.5.1"

# Captcha

gem "simple_captcha2", "~> 0.4.0", require: "simple_captcha"

# Background processing

gem "sidekiq", "~> 4.0"
gem "sinatra", "~> 1.4", ">= 1.4.7"

# Scheduled processing

gem "sidekiq-cron", "~> 0.4.1"

# Compression

gem "uglifier", "~> 2.7", ">= 2.7.2"

# Configuration

gem "configurate", "~> 0.3.1"

# Cross-origin resource sharing

gem "rack-cors", "~> 0.4.0", require: "rack/cors"

# CSS

gem "bootstrap-sass", "2.3.2.2", path: 'vendor/gems/bootstrap-sass-2.3.2.2'
gem "compass-rails",  "~> 2.0", ">= 2.0.5"
gem "sass-rails",     "~> 5.0", ">= 5.0.4"
gem "autoprefixer-rails", "~> 6.3", ">= 6.3.3.1"

# Database

ENV["DB"] ||= "mysql"

gem "mysql2", "~> 0.4.3" if ENV["DB"] == "all" || ENV["DB"] == "mysql"
gem "pg",     "~> 0.18.4" if ENV["DB"] == "all" || ENV["DB"] == "postgres"

gem "activerecord-import", "~> 0.11.0"

# File uploading

gem "carrierwave", "~> 0.10.0"
gem "fog",         "~> 1.34"
gem "mini_magick", "~> 4.4"
gem "remotipart",  "~> 1.2", ">= 1.2.1"

# GUID generation
gem "uuid", "~> 2.3", ">= 2.3.8"

# Icons

gem "entypo-rails", "~> 2.2", ">= 2.2.3"

# JavaScript

gem "backbone-on-rails", "~> 1.2"
gem "handlebars_assets", "~> 0.23.0"
gem "jquery-rails",      "~> 4.1"
gem "jquery-ui-rails",   "~> 5.0", ">= 5.0.5"
gem "js_image_paths",    "~> 0.1.0"
gem "js-routes",         "~> 1.2", ">= 1.2.4"

source "https://rails-assets.org" do
  gem "rails-assets-jquery",                              "~> 1.11", ">= 1.11.1" # Should be kept in sync with jquery-rails

  gem "rails-assets-markdown-it",                         "~> 6.0"
  gem "rails-assets-markdown-it-hashtag",                 "~> 0.4.0"
  gem "rails-assets-markdown-it-diaspora-mention",        "~> 0.4.0"
  gem "rails-assets-markdown-it-sanitizer",               "~> 0.4.1"
  gem "rails-assets-markdown-it--markdown-it-for-inline", "~> 0.1.1"
  gem "rails-assets-markdown-it-sub",                     "~> 1.0"
  gem "rails-assets-markdown-it-sup",                     "~> 1.0"
  gem "rails-assets-highlightjs",                         "~> 9.1"

  # jQuery plugins

  gem "rails-assets-jeresig--jquery.hotkeys",       "~> 0.2.0"
  gem "rails-assets-jquery-placeholder",            "~> 2.3", ">= 2.3.1"
  gem "rails-assets-jquery-textchange",             "~> 0.2.3"
  gem "rails-assets-perfect-scrollbar",             "~> 0.6.10"
  gem "rails-assets-jakobmattsson--jquery-elastic", "~> 1.6", ">= 1.6.11"
end

gem "facebox-rails", "~> 0.2.0"

# Localization

gem "http_accept_language", "~> 2.0", ">= 2.0.5"
gem "i18n-inflector-rails", "~> 1.0", ">= 1.0.7"
gem "rails-i18n",           "~> 4.0", ">= 4.0.8"

# Mail

gem "markerb",             "~> 1.1"
gem "messagebus_ruby_api", "~> 1.0", ">= 1.0.3"

# Parsing

gem "nokogiri",          "~> 1.6", ">= 1.6.8"
gem "redcarpet",         "~> 3.3", ">= 3.3.4"
gem "twitter-text",      "~> 1.13", ">= 1.13.3"
gem "roxml",             "~> 3.1", ">= 3.1.6"
gem "ruby-oembed",       "~> 0.9.0"
gem "open_graph_reader", "~> 0.6.1"

# Services

gem "omniauth",           "~> 1.3", ">= 1.3.1"
gem "omniauth-facebook",  "~> 3.0"
gem "omniauth-tumblr",    "~> 1.2"
gem "omniauth-twitter",   "~> 1.2", ">= 1.2.1"
gem "twitter",            "~> 5.16"
gem "omniauth-wordpress", "~> 0.2.2"

# Serializers

gem "active_model_serializers", "~> 0.9.4"

# XMPP chat dependencies
#gem "diaspora-vines",             "~> 0.2.0.develop"
gem "rails-assets-diaspora_jsxc", "~> 0.1.4", source: "https://rails-assets.org"

# Tags

gem "acts-as-taggable-on", "~> 3.5"

# URIs and HTTP

gem "addressable",        "~> 2.3", ">= 2.3.8", require: "addressable/uri"
gem "faraday",            "~> 0.9.2"
gem "faraday_middleware", "~> 0.10.0"
gem "faraday-cookie_jar", "~> 0.0.6"
gem "typhoeus",           "~> 1.0", ">= 1.0.1"

# Views

gem "gon",                     "~> 6.0", ">= 6.0.1"
gem "haml",                    "~> 4.0", ">= 4.0.7"
gem "mobile-fu",               "~> 1.3", ">= 1.3.1"
gem "will_paginate",           "~> 3.1"
gem "rails-timeago",           "~> 2.11"

# Logging

gem "logging-rails", "~> 0.5.0", require: "logging/rails"

# Reading and writing zip files

gem "rubyzip", "~> 1.1", ">= 1.1.7", require: "zip"

# Prevent occasions where minitest is not bundled in
# packaged versions of ruby. See following issues/prs:
# https://github.com/gitlabhq/gitlabhq/issues/3826
# https://github.com/gitlabhq/gitlabhq/pull/3852
# https://github.com/discourse/discourse/pull/238
gem "minitest"

# Windows and OSX have an execjs compatible runtime built-in, Linux users should
# install Node.js or use "therubyracer".
#
# See https://github.com/sstephenson/execjs#readme for more supported runtimes

# gem "therubyracer", :platform => :ruby

group :production do # we don"t install these on travis to speed up test runs
  # Administration

  gem "rails_admin", "~> 0.8.1"

  # Analytics

  gem "rack-google-analytics", "~> 1.2"
  gem "rack-piwik",            "~> 0.3.0",  require: "rack/piwik"

  # Click-jacking protection

  gem "rack-protection", "~> 1.5", ">= 1.5.3"

  # Process management

  gem "eye", "~> 0.7.0"

  # Redirects

  gem "rack-rewrite", "~> 1.5", ">= 1.5.1", require: false
  gem "rack-ssl",     "~> 1.4", ">= 1.4.1", require: "rack/ssl"

  # Third party asset hosting

  gem "asset_sync", "~> 1.1", require: false
end
