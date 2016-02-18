In Capabyra

```ruby
  page.has_css?('.css-rule', :visible => true) #the element has to be seen in the browswer
  page.has_css?('.css-rule', :visible => false) #the element exists in the DOM
  page.has_css?('.css-rule', :visible => :hidden) #the element is set to be `display:none`

```
