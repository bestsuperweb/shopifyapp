# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Managing versions and pushing
Steps to push to heroku (live)
rake assets:precompile
git status
git add .
git commit -m 'trying to fix heroku run rake db:migrate error'
git push heroku master

# cpi_shopify_app

#Added additional fields to quotations table:
rails generate migration add_more_fields_to_quotations product_variant_ids:string message_for_production:text status:string created_by_user_id:integer modified_by_user_id:integer