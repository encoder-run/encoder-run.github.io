source "https://rubygems.org"
ruby RUBY_VERSION

# Use Jekyll 4.0 or newer
gem "jekyll", "~> 4.0"

# Adding required gems to ensure future compatibility with newer Ruby versions
gem 'rexml'
gem 'base64'
gem 'bigdecimal'

# Jekyll plugins
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.15"
   gem "jekyll-paginate", "~> 1.1"
   gem "jekyll-seo-tag", "~> 2.6"
   gem "jekyll-gist", "~> 1.5"
   #gem "jekyll-livereload", "~> 0.2.2"
   gem "jekyll-avatar", "~> 0.7"
end

# Windows-specific gem, included conditionally for Windows platforms only
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]