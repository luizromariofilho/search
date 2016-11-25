# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
2.3.3

* System dependencies

*Gemfile*

gem 'searchkick'

*https://github.com/ankane/searchkick*

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

*model *

searchkick

*controller *
* Diz ao elastickick para pesquisar as keyrwords nos campos name e description *

@series = Series.search params[:keywords], fields: [:name, :description]

* Deployment instructions
