# README
# Rail-Started
# app/views/articles/show.html.erb

<li><%= link_to "Destroy", article_path(@article), data: {
                    turbo_method: :delete,
                    turbo_confirm: "Are you sure?"
                  } %></li>

Chane ========>

<li><%= button_to "Destroy", article_path(@article),
                  method: :delete,
                  data: { turbo_confirm: "Are you sure?" } %></li>

                  
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


