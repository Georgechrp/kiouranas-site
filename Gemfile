source "https://rubygems.org"

# Jekyll και απαραίτητα gems
gem "jekyll", "~> 4.4.1"
gem "csv"
gem "base64"
gem "logger"
gem "webrick"

# Theme (δεν χρειάζεται το minima αν έχεις δικό σου layout)
# gem "minima", "~> 2.5" # --> ΜΗΝ το βάλεις αν ΔΕΝ χρησιμοποιείς το minima theme

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
end

# Υποστήριξη Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
