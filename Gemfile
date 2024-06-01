# frozen_string_literal: true
source "https://rubygems.org"

gem 'inherited_resources', path: '~/dev/inherited_resources'

group :development, :test do
  gem "rake"

  gem "cancancan"
  gem "pundit"

  gem "draper"
  gem "devise"

  gem "rails", "~> 7.1.0"

  gem "sprockets-rails"
  gem "ransack", ">= 4.1.0"
  gem "formtastic", ">= 5.0.0"

  gem "cssbundling-rails"
  gem "importmap-rails"
end

group :test do
  gem "cuprite"
  gem "capybara"
  gem "webrick"

  gem "simplecov", require: false # Test coverage generator. Go to /coverage/ after running tests
  gem "simplecov-cobertura", require: false
  gem "cucumber-rails", require: false
  gem "cucumber"
  gem "database_cleaner"
  gem "launchy"
  gem "parallel_tests"
  gem "rspec-rails"
  gem "sqlite3", "~> 1.7", platform: :mri # FIXME: relax this dependency when rails/rails#51636 will be released

  # Translations
  gem "i18n-tasks"
  gem "i18n-spec"
  gem "rails-i18n" # Provides default i18n for many languages
end

group :rubocop do
  gem "rubocop"
  gem "rubocop-capybara"
  gem "rubocop-packaging"
  gem "rubocop-performance"
  gem "rubocop-rspec"
  gem "rubocop-rails"
end

group :docs do
  gem "yard" # Documentation generator
  gem "kramdown" # Markdown implementation (for yard)
end

gemspec path: "."
