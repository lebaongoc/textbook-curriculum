# Creating an API

## Section 1 Generating JSON responses

The code in this section is to belong to a `PetsController`.

```ruby
def destroy
  pet = Pet.find_by(id: params[id])

  pet.destroy

  render json: {ok: true, pet: pet }
end
```

1.  Looking at the above method, what is wrong with it?  What would you change?




2.  Fill in the missing lines below:


```ruby
def update
  pet = Pet.find_by(params[:id])

  if pet
    pet.update(name: params[:pet][:name], age: params[:pet][:age],
      human: params[:pet][:human])

      # Your code here

  else
    # More code goes here


end
```

## Section 2 Testing an API

Fill in the test below to verify the `update` controller method.

```ruby
describe PetsController do
...

  describe 'update' do












  end
end
```
