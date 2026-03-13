source "https://rubygems.org"

# GitHub Pages gestiona la versión de Jekyll
gem "github-pages", group: :jekyll_plugins

# Tema (si quieres usar Minima)
gem "minima", "~> 2.5"

# Plugins permitidos por GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows y JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Booster para Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]