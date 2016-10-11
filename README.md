# Chad the Chat application

### To run the application

- ``` Git git clone git@github.com:thandon263/chadbot_comp.git ```

- ``` Git bundle install ```
- ``` Git rake db:migrate or bundle exec rake db:migrate ```

* It will depend on the version of rails you are using

``` Ruby

    def __adt__  
      "This is a test!"
    end

    puts __adt__

    ActiveSupport.on_load(:action_controller) do
      wrap_parameters format: [:json]
    end

    # To enable root element in JSON for ActiveRecord objects.
    # ActiveSupport.on_load(:active_record) do
    #   self.include_root_in_json = true
    # end
```

## Our models for the app

- A chat room will have a topic
- and it will have many messages.
- A message will have content, and it will belong to a user and belong to a chatroom.
- A user will have a username, and will have many messages.


## TO get started:

1. Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
