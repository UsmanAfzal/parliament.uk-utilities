source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'

# Use Puma as the app server
gem 'puma', '~> 3.7'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Use HAML for our view rendering
gem 'haml'

# Use Parliament-Ruby for web requests
gem 'parliament-ruby', '~> 0.7'

# Use Parliament-Opensearch to handle our Opensearch requests
gem 'parliament-opensearch', '~> 0.2'

# Use bandiera-client for feature flagging
gem 'bandiera-client'

# Use Pugin for front-end components and templates
gem 'pugin', '~> 0.8'

# Use dotenv to override environment variables
gem 'dotenv'

# # Use sanitize to prevent cross site scripting
# gem 'sanitize'

# Use Airbrake for error monitoring
gem 'airbrake'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rake'
  gem 'capybara'
  gem 'rspec-rails'
  gem 'simplecov', '~> 0.14', require: false
  gem 'vcr'
  gem 'webmock'
  gem 'rubocop'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
