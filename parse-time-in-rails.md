```ruby
Time.zone = 'UTC'
Time.zone.parse(time_string)
```
or

```ruby
Time.zone.parse(time_string).in_time_zone('UTC')
```
