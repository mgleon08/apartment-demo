# Apartment Demo


# Run postgres

```ruby
docker run -e POSTGRES_DB=apartment-demo_development -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:11.1
```


# Rails

```ruby
rake db:create
rake db:migrate
rails s
```
