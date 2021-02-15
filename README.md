# Bankr

Bankr is a mock banking website where a user can simulate accessing accounts at multiple banks, transferring funds between accounts, and requesting loans from specific banks. Users can create, edit, and update a user profile with a username and password. Usernames are validated for uniqueness, and passwords for length. 

# Getting started
* Fork and clone the the repo.
From the main project directory:
* Run 'bundle install'
* Run 'rails db:migrate' to create the database 
* Run 'rails db:seed' to populate your new database with some seed data.
Once you have taken all of the steps above, you will be able to simulate the banking experience from your web browser. 

# Prerequisites
* Ruby version 2.6.1
* Bundler

# Installing
```
# To install Ruby run the line below
rvm install 2.6.1
# To use that version of ruby run the line below
rvm use 2.6.1
# To make sure it worked run the line below. If you get =* ruby-2.6.1 you should be good to go
run rvm list 
```
```
# To install bundler run the line below
gem install bundler
```

# Deployment
```
# To host the site locally for testing, run the line below from the main project directory 
rails s
If you see "
* Listening on tcp://127.0.0.1:3000
* Listening on tcp://[::1]:3000
"
in the terminal, you should be good to go. Now you can navigate to localhost:3000 in your web browser (Chrome preferred) to view the site.
```

# Built With
* Ruby - Served as the base language
* Rails - MVC pattern

# Authors
* [Johnnathan Baxter](https://github.com/jbaxter6)
* [Ian MacKinnon](https://github.com/ianmcknnn)
