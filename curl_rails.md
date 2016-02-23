To deal with the authenticity_token in rails, 
Step 1: `curl http://example.com --cookie-jar | grep csrf`
Step 2: copy&paste the token to `curl http://example.com -d "authenticity_token=foobar"`


https://robots.thoughtbot.com/curling-with-rails-authenticity-token
