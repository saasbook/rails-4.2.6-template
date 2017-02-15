== README

Be sure to change the app's name in `config/application.rb` before doing
anything!

This app framework includes:

* Ruby 2.3.1
* Rails 4.2.6
* Rspec 3 in lieu of Test::Unit
  * `rails_helper.rb` file that runs SimpleCov 
  * `rails_helper.rb` mixes in FactoryGirl's object creation methods
* Cucumber 2 
  * including `cucumber_rails_training_wheels` default step defs
  * including database cleaner gem
  * configured to mix in FactoryGirl's object creation methods 
* Jasmine, for Javascript testing
* Figaro for managing secrets
* Haml, with `app/views/layouts/application.html.haml` in place
* Bootstrap 3
  * using the `bootstrap-sass` gem and Bootstrap 3 ported from
less to sass
  * default `app/assets/stylesheets/application.css` renamed to
  `application.scss` to serve everything via Sass asset pipeline
  * `bootstrap-sprockets` included in `application.scss`
  * Bootstrap JS files required in `app/assets/javascripts/application.js`
* Production gems for Heroku deployment

You'll probably need the [Heroku
Toolbelt](https://toolbelt.heroku.com). On OS X you can `brew install
heroku`.
