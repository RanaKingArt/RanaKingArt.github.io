source "https://rubygems.org"

# This Gemfile is specifically configured for GitHub Pages.

# Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.

# GitHub Pages Ruby Gem
# A simple Ruby Gem to bootstrap dependencies for setting up and 
# maintaining a local Jekyll environment in sync with GitHub Pages.
gem "github-pages", "~> 207", group: :jekyll_plugins

# The GitHub Pages gem also comes with several command-line tools, 
# contained within the github-pages command.
# Run github-pages command as below to list dependency versions:
# 
#     bundle exec github-pages versions
# 
# This will list all the includeed gems and their versions.

# If you have any plugins, put them here!
# Caution: Only available when previewing your Jekyll site locally.
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.6"
# end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# kramdown v2 ships without the gfm parser by default. If you're using
# kramdown v1, comment out this line.
gem "kramdown-parser-gfm"

