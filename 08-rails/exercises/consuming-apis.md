# Consuming An API Exercise

If the API Call:

## Section 1 Using JSON 

```ruby
response = HTTParty.get("https://dog.ceo/api/breed/#{ @breed }/list")
```

results in:

```json
[
    {
        "id": 1,
        "name": "Muffin",
        "location": "Kansas City, NE",
        "description": "A fluffy ball of fun!"
    },
    {
        "id": 2,
        "name": "Peaches",
        "location": "New York City, NY",
        "description": "Tiny but Fierce!!"
    },
    {
        "id": 3,
        "name": "Bruno",
        "location": "Seattle, WA",
        "description": "An old guy who loves to cuddle"
    },
]
```

How could you loop through each dog, and print out their names to the terminal?

```ruby








```

## Section 2 API Knowledge

1.  What formats do web APIs return data in?  


2.  With the following HTTParty call,

`response = HTTParty.get("https://dog.ceo/api/breeds/image/random")`

Describe what the following return:

a.  `response.body`
b.  `response.code`
c.  `response.message`
d.  `response.headers`

2. Why do some APIs require authentication?  



3.  What purpose does an API Wrapper serve?