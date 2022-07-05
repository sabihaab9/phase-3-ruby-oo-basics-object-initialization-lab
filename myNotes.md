# Object Initialization

## Learning Goals
- The `#initialize` method is a method that is called _automatically_ whenever `.new` is used.


let's define our `#initialize` method to contain the functionality of the `#breed=`method, so that a dog instance will get a breed assigned to it right away when it is created, without us having to explicitly use the `#breed=` method.

```ruby
class Dog
  attr_reader :breed

  def initialize(breed)
    @breed = breed
  end

end
```



