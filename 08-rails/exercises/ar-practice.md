# Active Record Practice Exercises

The following two models are to be used in an online game application.

![model erd](./images/game_erd.png)

## Section 1 Relationships

1.  Modify the following model classes to define the relationship.

```ruby
# app/models/user.rb
class User < ApplicationRecord




end
```


```ruby
# app/models/gameresult.rb
class GameResult < ApplicationRecord




end
```

2.  How could you add the following methods to the two classes:

```ruby
# app/model/user.rb
class User < ApplicationRecord


  # Returns the percentage 0-100
  # of games the user has won
  def win_percentage







  end

  # Returns the user's average score
  def average_score




  end
end

```

3.  Looking at the Ada Books project, what methods do the following ActiveRecord relations provide?

    3.1. In the Author class, `has_many :books`

    a. `.authors`
    b. `.books`
    c. `.author`
    d. `.book`

    3.2. In the Author class, `has_many :books`

      a. `.authors`
      b. `.books`
      c. `.author`
      d. `.book`

    3.3  Looking at the User and GameRecord classes above, what methods do the relationships provide these classes?
