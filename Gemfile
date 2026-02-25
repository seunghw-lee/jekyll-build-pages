# frozen_string_literal: true

# This file is essential because it's referenced by a lot of repositories
# such as my blog, diary, devlog, and other ones whose owners use the Action!

source 'https://rubygems.org'

gem 'jekyll'
gem 'jemoji'
gem 'minima'
gem 'jekyll-theme-chirpy'

# If you're using the MathJax math engine instead, free to remove the line below:
gem "kramdown-math-katex"

# A JavaScript runtime for Ruby that helps with running the katex gem above.
gem "duktape"

# Required for `jekyll serve` in Ruby 3
gem "webrick"


group :development do
  gem 'rubocop'
end

group :jekyll_plugins do
  gem 'jekyll-default-layout'
  gem 'jekyll-optional-front-matter'
  gem 'jekyll-readme-index'
  gem 'jekyll-redirect-from'
  gem 'jekyll-commonmark'
  gem 'jekyll-feed'
  gem 'jekyll-paginate'
  gem 'jekyll-remote-theme'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
  gem 'jekyll-polyglot'

  gem "jekyll-relative-links"
  gem "jekyll-titles-from-headings"
  gem "jekyll-include-cache"

  # Non-Github Pages plugins:
  gem "jekyll-last-modified-at"
  gem "jekyll-compose"
end

gem 'wdm' if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?

