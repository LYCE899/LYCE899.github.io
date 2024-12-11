source "https://rubygems.org"

# GitHub Pages gem, qui gère automatiquement les versions compatibles de Jekyll
gem "github-pages", group: :jekyll_plugins

# Plugins supplémentaires si nécessaire
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Support Windows et JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Booster la performance de surveillance de fichiers sur Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
