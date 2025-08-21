source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "webrick", "~> 1.7"
gem "logger", "~> 1.5"
gem "csv", "~> 3.2"
gem "base64", "~> 0.2.0"
gem "bigdecimal", "~> 3.1"
gem "ostruct", "~> 0.5.0"

# Keep your existing plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tidy"
end

gem 'jekyll-sitemap'
gem 'kramdown-math-katex'

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]