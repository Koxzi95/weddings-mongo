source 'https://rubygems.org'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
group :development, :test do
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # rspec for dependency
  gem 'rspec', '~> 3.2.0'
  # rspec for BDD tests (Behaviour Driven Development)
  gem 'rspec-rails', '~> 3.2.1'
  # Factory Girl for testing setup
  gem 'factory_girl_rails', '~> 4.5.0'
  # Database Cleaner for testing
  gem 'database_cleaner', '~> 1.4.0'
end

group :production do
  gem 'rails_12factor'
end

# Add versions (gemnasium)
gem 'mongoid', '~> 4.0.0'
gem 'mongoid-grid_fs', github: 'ahoward/mongoid-grid_fs'
gem 'mongoid-paperclip', :require => 'mongoid_paperclip'

gem 'money-rails'

gem 'devise', '~> 3.4.1'

gem 'cancancan', '~> 1.10.1'

# Viewable to make rooms viewable.
gem 'viewable', '~> 0.5.18'

# Mail Form gem for sending mail directly from a form.
gem 'mail_form', '~> 1.5.1'

#my-bookable
gem 'my-bookable', :git => 'https://github.com/staceysmells/bookable.git', :branch => 'master'

# Active Admin
gem 'activeadmin', :git => 'https://github.com/activeadmin/activeadmin.git', :branch => 'master'

# Bundle on OSX and Linux only. (including deployment)
platforms :ruby do
  # Unicorn for worker process management (won't bundle on non-unix)
  # => should now only bundle on OSX & Linux. And hopefully deploy!
  gem 'unicorn', '~> 4.9.0'
  # CLI gem for atom-beautify package. (Ctrl+Alt+B)
  gem 'ruby-beautify', '~> 0.97.3'
end

platforms :mingw, :mswin, :x64_mingw, :jruby do
  # tz-info for windows timezone data.
  gem 'tzinfo-data', '~> 1.2015.3'
  # Responders gem, required on windows for viewable
  gem 'responders', '~> 2.0'
end
