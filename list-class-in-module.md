```ruby
MyModule.constants.select {|c| Class === Mymodule.const_get(c) }
```
