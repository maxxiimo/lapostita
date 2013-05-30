source 'https://rubygems.org'

gem 'rails', '3.2.13'

group :development, :test do
  gem 'sqlite3', '1.3.5'

  # http://railscasts.com/episodes/402-better-errors-railspanel
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :production do
  gem 'pg', '0.12.2'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.5'
  gem 'coffee-rails', '~> 3.2.2'
  gem 'uglifier',     '>= 1.2.3'

  # Compass specific gems.
  gem 'compass-rails'
  gem 'oily_png'
  gem 'susy'
end

gem 'jquery-rails', '~> 2.0.0'
gem 'fog'

# Refinery CMS
gem 'refinerycms', '~> 2.0.0', :git => 'git://github.com/refinery/refinerycms.git', :branch => '2-0-stable'

# Specify additional Refinery CMS Extensions here (all optional):
gem 'refinerycms-i18n', '~> 2.0.0'
#  gem 'refinerycms-blog', '~> 2.0.0'
#  gem 'refinerycms-inquiries', '~> 2.0.0'
#  gem 'refinerycms-search', '~> 2.0.0'
#  gem 'refinerycms-page-images', '~> 2.0.0'
