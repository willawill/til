``ruby
require 'rack'
require 'uri'

Rack::Utils.parse_query(URI.parse(link).query)
```
