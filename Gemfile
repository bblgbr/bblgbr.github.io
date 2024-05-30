source "https://rubygems.org"


gem 'faraday-retry'
gem 'backports'
gem 'kramdown'
gem 'puma'


# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
    # gem 'devlopr', '~> 0.4.5'
    gem 'jgd'
    gem 'jekyll-feed'
    gem 'jekyll-paginate'
    gem 'jekyll-gist'
    gem 'jekyll-seo-tag'
    gem 'jekyll-sitemap'
    gem 'jekyll-admin'
end


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :install_if => Gem.win_platform?
gem "webrick"
gem "rack", '2.2.6.2'
