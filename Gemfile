source 'https://rubygems.org'
ruby '2.2'

# rack-jekyll fails to install under US_ASCII which is what the Jenkins
# slaves are set to.
Encoding.default_external=Encoding::UTF_8
Encoding.default_internal=Encoding::UTF_8

gem 'git', "~> 1.2"
gem 'typogruby', "~> 1.0"
gem 'jekyll', "~> 2.0"
gem 'jekyll-paginate'
gem 'jekyll-plantuml'
gem 'jekyll-sitemap'
gem 'kramdown', "~> 1.3"
# Until https://github.com/adaoraul/rack-jekyll/pull/22 is accepted
#gem 'rack-jekyll', :git => 'https://github.com/awood/rack-jekyll'
gem 'rack-jekyll'
gem 'nokogiri'
gem 'stringex'
gem 'rack', "=1.5.2"
gem 'rack-rewrite'
gem 'thin'

group :development do
  gem 'httparty'
  gem 'thor'
  gem 'safe_yaml'
  gem 'rack-livereload'
  gem 'guard-livereload'
end

