```ruby
describe FooController do
  controller do
    def index
    end
  end

  it 'has index action' do
    get :index

    expect(response).to be_success
  end

end
```
