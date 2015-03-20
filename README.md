# Rails AngularJS template
Rails application template setting up rails to work with angular.

# Usage
Clone the repo and then use the option `-m angular_template/angular_template.rb` when you create a new rails project.

### Options
You can choose to setup git and create an initial commit.

## Gems included
gem 'pg'
gem 'pry-rails'
gem 'angularjs-rails'
gem 'ngannotate-rails'
gem 'angular-ui-router-rails', git: 'https://github.com/iven/angular-ui-router-rails.git'

### development and testing
gem 'rspec-rails'
gem 'guard', require: false
gem 'spring-commands-rspec'
gem 'guard-rspec'
gem 'factory_girl_rails'
gem "better_errors"

### Removed gems
gem 'turbolinks'
