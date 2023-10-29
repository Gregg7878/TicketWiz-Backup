source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.4"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.8"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

gem 'bcrypt', '~> 3.1' # Specify a compatible version without the patch level

gem "active_model_serializers", "~> 0.10" # Specify a compatible version without the patch level

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem "rack-cors"

# Add rest-client for mpesa stk
gem 'rest-client'

# Group specific gems for development
group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
  # Specify additional development gems if needed
end

# Add the specific version of the 'faraday' gem
gem 'faraday', '~> 1.7'

# If you decide to uncomment and use the 'ruby-daraja' gem, specify its version:
# gem 'ruby-daraja', '~> 1.0'
