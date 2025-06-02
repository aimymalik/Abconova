#after any changes to the Gemfile, execute bundle update!
source "https://rubygems.org"

# Consider updating Jekyll. Jekyll 4.3.3 is the latest 4.x as of my last update.
# If you want to be safer, try a specific recent patch for 4.2.x if available,
# or go for the latest 4.x.
gem "jekyll", "~> 4.3.0" # This will get the latest 4.3.x version

gem "jekyll-agency"

# Add gems from warnings
gem "csv"
# base64 is typically a core part of Ruby, but if the warning persists after bundle install,
# you might need to add it. For now, let's assume it's covered.
gem "bigdecimal"

# For Windows (Codespaces run on Linux, so this won't apply there but good to keep if you ever run on Windows)
gem "wdm", ">= 0.1.0", :platforms => [:mswin, :mingw]

# Add any other plugins you have
# gem "jekyll-feed", "~> 0.12"
# gem "jekyll-seo-tag", "~> 2.7"
# ... etc.