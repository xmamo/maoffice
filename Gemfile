source "https://rubygems.org"

group :jekyll_plugins do
  gem "github-pages"
  gem "jekyll-compose"
end

gem "webrick"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem and associated
# library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
