# Active Record Practice Exercises - Custom Methods & Relationships

The following two models are to be used in an online game application.

![model erd](./images/game_erd.png)

## Section 1 Relationships

1.1  Modify the following model classes to define the relationship.

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

1.2 What methods do these relationships provide to the models?

Specifically what new method appears in `User` instances with the new code you added above.

What gets added to `GameResult` instances when you add the relationship?


What data types do these methods return?

## Section 2 Custom Methods

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
