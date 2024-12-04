# frozen_string_literal: true

ruby '3.3.1'

source 'https://rubygems.org'

gem 'jekyll', '>= 3.8.5'

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.6'
  gem 'jekyll-gallery-generator', git: 'https://github.com/evaniainbrooks/jekyll-gallery-generator'
  gem 'jekyll-paginate', '~> 1.1.0'
  gem 'jekyll-sitemap'
end

group :development do
  gem 'standardrb'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.0' if Gem.win_platform?
