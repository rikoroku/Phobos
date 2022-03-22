source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.1'

gem 'rails', '~> 7.0.2', '>= 7.0.2.3'
gem 'sprockets-rails' # The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'mysql2', '~> 0.5'
gem 'puma', '~> 5.0'
gem 'importmap-rails' # Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem 'turbo-rails' # Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'stimulus-rails' # Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'jbuilder'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem 'kredis'
# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem 'bcrypt', '~> 3.1.7'
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'bootsnap', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'sassc-rails'
gem 'slim-rails'
# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem 'image_processing', '~> 1.2'
gem 'seed-fu'
gem 'dotenv-rails'
gem 'config'

group :test do
  gem 'rspec-rails', '~> 5.1'
  gem 'capybara', '~> 3.36'
  gem 'cuprite'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'test-prof'
end

group :development, :test do
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'rubocop-performance'
  gem 'rubocop-rspec'
  gem 'slim_lint', require: false
end

group :development do
  gem 'web-console' # Use console on exceptions pages [https://github.com/rails/web-console]
  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem 'rack-mini-profiler'
  gem 'spring' # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem 'brakeman', require: false
  gem 'bullet'
end
