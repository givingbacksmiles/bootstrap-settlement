# Bootstrap Settlement

#### Jumpstart your Rails applications using Bootstrap 3.  All setup and ready to go.  Easy to use mixins and gems pre-installed for immediate design or development.
****

**Rails version:** 4.0.2


**Ruby version:** 2.0.0


**Database:** PostgreSQL

*Postgres only because it works better for use with Heroku's Cedar stack.*

****


#### Installation and Setup

1.  Fork or clone the repo.
  1. Rename the application...
2.  copy the database.yml.example
  1.  create a new file under the config root directory called database.yml
  2.  paste the database.yml.example in this file and insert your username and password.
  3.  replace bootstrap-settlement with your application name for databases in database.yml
3.  `bundle install`
4.  `rake db:create`
5.  `rake db:migrate`
6.  `rails s` 
7.  Check out the links towards the bottom for some really awesome resources for Bootstrap 3 design!


****

#### Additions to the Gemfile
1.  `gem 'pg'`
2.  `gem 'rails_12factor'`
3.  `gem 'bootstrap-sass'`
3.  `gem 'rails_layout'`

****


**Feel free to submit suggestions to this settlement [here].  I am looking forward to your opinions and enhancements.**

[here]:https://github.com/viaforge/bootstrap-settlement/issues/new