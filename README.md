FIRST TIME DEPLOY
=================

* git push heroku
* heroku run bundle exec padrino rake dm:migrate
* heroku run bundle exec padrino console
* Account.new(:name => 'First', :surname => 'Last', :email => 'someone@domain.com', :password => 'mypass', :password_confirmation => 'mypass', :role => 'admin').save