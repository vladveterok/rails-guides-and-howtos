# Big and beautiful guide on Webpack in Rails:
   https://gist.github.com/maxivak/2612fa987b9f9ed7cb53a88fcba247b3#jquery-jquery-ui
   
# How to install jQuery and jQuery-ui in Rails 6:
   https://www.dailysmarty.com/posts/drag-and-drop-with-jquery-in-rails-6
   https://stackoverflow.com/questions/57555708/rails-6-how-to-add-jquery-ui-through-webpacker
   
### Comments:
    in app/javascript/packs/application.js -- require('jquery-ui'); didn't work for me, 
    instead: require('jquery-ui-dist/jquery-ui') 

# How to install Bootstrap 4 in Rails 6
   https://gorails.com/episodes/how-to-use-bootstrap-with-webpack-and-rails?autoplay=1
    
# How to install RSpec in Rails 6
   https://github.com/rspec/rspec-rails

### Comments:
    The thing is that it's important to explicitly add >= 4 version of RSpec into Gemfile like so:
    gem 'rspec-rails', '~> 4.0.0.rc1'
    
# How to setup RSpec, Capybara, FactoryBot, and DatabaseCleaner with Devise:
   https://matthewhoelter.com/2019/09/12/setting-up-and-testing-rails-6.0-with-rspec-factorybot-and-devise.html
   https://medium.com/@yutafujii_59175/a-simple-login-test-with-rspec-devise-factorybot-in-rails-29aeb2ebc4ab
   https://medium.com/better-programming/how-to-set-up-rails-with-rspec-capybara-and-database-cleaner-aacb000070ef
   
