source "https://rubygems.org"

# Jekyll version
gem "jekyll", "~> 4.3.4"

# The default theme for new Jekyll sites
gem "minima", "~> 2.5"

# If you want to use GitHub Pages, remove the "gem 'jekyll'" above and uncomment the line below.
# gem "github-pages", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Required for CSV support (since it is missing in Ruby 3.4)
gem "csv"

# Required for logger support (since it is missing in Ruby 3.4)
gem "logger"
gem "base64"
gem "sassc"


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
