source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring', '~> 2.1.0'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rspec-rails', '~> 3.9'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "actionview", ">= 5.2.4.2"

gem 'rails', '~> 5.0.7', '>= 5.0.7.2'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.0'
gem 'jbuilder', '~> 2.5'
gem 'bcrypt', '~> 3.1.7'
gem 'jwt', '~> 2.2.1'
gem 'fast_jsonapi', '~> 1.5'
gem 'faker', '~> 2.11.0'
gem 'swagger-docs', '~> 0.2.7'
gem 'logger', '~> 1.4.2'
gem 'rack-cors', '~> 1.1.1'
gem 'rack-attack', '~> 6.2.2'