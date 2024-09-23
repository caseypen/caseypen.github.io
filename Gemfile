source "https://rubygems.org"

# Specify the Jekyll version you want to use.
gem "jekyll", "~> 4.3" # Adjust to the latest stable version if desired.

# Include plugins and other dependencies within the :jekyll_plugins group.
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"    # <-- Added jekyll-paginate
  gem "jekyll-gist" 
  gem "faraday-retry"
  gem "jekyll-redirect-from" # <-- Added jekyll-redirect-from

  # gem "hawkins"           # Uncomment if you determine it's necessary and compatible.
end

# Include 'wdm' for Windows platforms to ensure smooth file system monitoring.
gem "wdm", "~> 0.1.0" if Gem.win_platform?
