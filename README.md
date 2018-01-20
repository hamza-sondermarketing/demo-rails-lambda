# README

Simple demo rails app. It has a demo controller that shows successful access to the database.

## Setup

```sh
git clone https://github.com/tongueroo/demo-rails
cd demo-rails
cp config/database{.example,}.yml
# edit config/database.yml with the RDS endpoint
rails s # start server
```

Now you can should be able to go to the url endpoint to see the demo page. Here's the relevant code:

* [app/controllers/demo_controller.rb](app/controllers/demo_controller.rb)
* [app/views/demo/index.html.erb](app/views/demo/index.html.erb)
