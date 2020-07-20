source 'https://rubygems.org'
gem "jekyll", "4.0.0"

group :jekyll_plugins do
  gem 'jekyll-redirect-from', '>= 0.15.0'
  gem 'jekyll-sitemap', '>= 1.3.0'
  gem 'jekyll-paginate'
  gem 'rouge'
end

require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
  gem 'rb-fsevent', '<= 0.9.4'
end
