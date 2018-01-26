# README

# Tutorial Location

## Part one
https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one

## Part two
https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-two

## Part three
https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-three


### sign up
http :3000/signup name=mccree email=mccree@email.com password=testing password_confirmation=testing

### log in
http :3000/auth/login email=mccree@email.com password=testing

### create todos
http POST :3000/todos title=Beethoven \
> Authorization:'auth_token'

### retrieve all todos without version
http :3000/todos \
> Authorization:'auth_token'

### create todo item
http POST :3000/todos/1/items name='Listen to Don Giovanni' Accept:'application/vnd.todos.v1+json' Authorization:'auth_token'

### retrieve all todos with version
http :3000/todos Accept:'application/vnd.todos.v1+json' Authorization:'auth_token'
