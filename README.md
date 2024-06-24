```ruby
ruby main.rb

db_store = DiskStore.new("database.db")

# Setting values in store
db_store.put("Anime", "Bluelock")
db_store["Nagi"] = "Baller"

# Getting values from store
db_store["Anime"]
db_store.get("Nagi")

# Listing keys
db_store.keys
```
