# APP to TRYOUT out things ...

This demo app is based on Ruby 3.1 and Rails 7.0, uses

* [Authentication Zero](https://github.com/lazaronixon/authentication-zero)
for simple- and 2FA-authentication (rails generate authentication --two-factor)
* [Letter Opener](https://github.com/ryanb/letter_opener) to show mail messenges
* ...

To get the application up and running:

* clone the repo
* run 'bundle install'
* create database 'rails db:drop:migrate'
* start the server 'rails s'

TODO
* run the test suite
* Services (job queues, cache servers, search engines, etc.)
* deployment instructions to glcloud
