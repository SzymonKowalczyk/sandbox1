
ruby '2.3.3', engine: 'jruby', engine_version: '9.1.17.0'

# These dependencies are forked in order to remove the LGPL'd setup.rb file:
gem 'abstract', '1.0.0.d86eb2255aefb5c0ce4dd2351dbbf4b9e22264ad'
gem 'activeresource-response'
gem 'bcrypt-ruby'
gem 'blue_ibm_catalog_import', '= 3.0.2'
gem 'equivalent-xml', '0.6.0'
gem 'erubis', '2.7.0.1.ed3659f9fdc6659f69fce047e9f57f0289d903d8'
gem 'excon'
gem 'formtastic'
gem 'fortitude', '0.9.6.293aadedf350b2cd80f3db885c9d702351d3e38b'
gem 'haml'
gem 'htmlentities'
gem 'http_accept_language', '1.0.1.1.a75d7431d8bba418294b29d43dd8f546ebbffe23'
gem 'inherited_resources', '1.9.0.76ad413008d729c4b764caff0f46952d13a4ef62'
gem 'json'
gem 'json-schema', '~> 2.5.1'
gem 'mail', require: nil
gem 'nokogiri', '1.6.8.1.fc90d7a1defdc17564eb72b85bf8c2e0'
gem 'rails', '= 5.1.7'
gem 'rest-client', '= 1.8.0'
gem 'ri_cal', '0.8.8.764df9150215e9a0d2560b4549d758cc'
gem 'rubyzip'
gem 'rufus-scheduler', '~> 3.1.2'
gem 'sequel', '4.24.0.9d792a04e8ef0cea89ab8b94522b4942'
gem 'tzinfo-data'
gem 'uuidtools', '= 2.1.5.de05809f0c8ad134e3f30aae50959f3b'
gem 'zip-zip'

# Asset pipeline
# Available in all environments but isn't packaged
group :assets do
  gem 'compass-blueprint', '~> 1.0.0'
  gem 'compass-rails'
  gem 'i18n-js', '~> 3.0.0.rc12'
  gem 'non-stupid-digest-assets'
  gem 'sass', '3.4.22.9f9d211398c5530537031685b0101c30'
  gem 'sass-rails'
  gem 'therubyrhino'
  gem 'uglifier', '~> 3.0.0'
end

group :development, :test do
  gem 'awesome_print'
  gem 'jasmine', '2.99.37d002d4977c983aed8edc374e3adb58dbae390b'
  gem 'jasmine_junitxml_formatter'
  gem 'machinist', '= 1.0.6.be28caa89f36251c66619ca721440459a3b7e219'
  gem 'rails-controller-testing'
  gem 'simplecov', require: nil
  gem 'simplecov-html', '= 0.8.0.1.0df13868c3dd9a42c7a6c5e5e2fbde205e607ac2', require: nil
  gem 'sprockets'
end

group :development do
  gem 'charlock_holmes-jruby'
  gem 'jruby-jars', '9.1.17.0'
  gem 'jruby-rack'
  gem 'puma'
  gem 'rubocop', '0.50.0', require: false
  gem 'warbler', '2.0.3'
  gem 'ya2yaml'
end

group :test do
  gem 'ci_reporter_cucumber'
  gem 'ci_reporter_rspec'
  gem 'rspec-rails'
  gem 'timecop'
end

group :cucumber do
  gem 'bermuda'
  gem 'capybara'
  gem 'chronic'
  gem 'cucumber'
  gem 'cucumber-rails'

  # See https://github.com/bigfix/phantomjs-gem/tree/more_windows_support
  gem 'phantomjs', '= 1.9.8.0.efc930e9b3a2f8ed9ba851007d5c86beafd234e6'

  # Bug in 1.6.0 with hidden elements, see https://github.com/teampoltergeist/poltergeist/issues/628
  gem 'poltergeist', '~> 1.9'
end
