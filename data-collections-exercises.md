### Arrays

Starting with the following array...

```rb
planeteers = ["Earth", "Wind", "Captain Planet", "Fire", "Water"]
```

Access the second value in `planeteers`.

```rb
planeteers[1]
```

Add "Heart" to the end of `planeteers`.

```rb
planeteers.push("planeteers")

```

Remove "Captain Planet" from the array **(without using a method)**.

```rb
p planeteers - ["Captain Planet"]
```

Combine `planeteers` with `rangers = ["Red", "Blue", "Pink", "Yellow", "Black"]` and save the result in a variable called `heroes`.

```rb
 planeteers = ["Earth", "Wind", "Captain Planet", "Fire", "Water"] 
 
 rangers = ["Red", "Blue", "Pink", "Yellow", "Black"]

heroes =planeteers+rangers
 
p heroes```

Alphabetize the contents of `heroes` using a method. [The Ruby documentation might help](http://ruby-doc.org/core-2.6.1/Array.html).

```rb
p heroes.sort
```

Randomize the contents of `heroes` using a method. [The Ruby documentation might help](http://ruby-doc.org/core-2.6.1/Array.html).

```rb
# Your answer here
```

#### Bonus

Select a random element from `heroes` using a method. [The Ruby documentation might help](http://ruby-doc.org/core-2.6.1/Array.html).

```rb
heroes.shuffle
```

Select all elements in `heroes` that begin with "B" using a method. [The Ruby documentation might help](http://ruby-doc.org/core-2.6.1/Array.html).

```rb
p heroes.select{|item| item.include?("B") } 
```

### Hashes

Initialize a hash called `ninja_turtle` with the properties `name`, `weapon` and `radical`. They should have values of "Michelangelo", "Nunchuks" and `true` respectively.

```rb
ninja_turtle = {
ninja_turtle:"Michelangelo" ,

weapon:"Nunchuks" ,
radical:'true'

}
```

Add a key `age` to `ninja_turtle`. Set it to whatever numerical value you'd like.

p ninja_turtle.keys+[:age]


Remove the `radical` key-value pair from `ninja_turtle`.

```rb
p ninja_turtle.keys-[:radical]

```

Add a key `pizza_toppings` to `ninja_turtle`. Set it to an array of strings (e.g., `["cheese", "pepperoni", "peppers"]`).

```rb
ninja_turtle.keys+[:pizza_toppings]
 
 ninja_turtle[:pizza_toppings]= ["cheese", "pepperoni", "peppers"]
```

Access the first element of `pizza_toppings`.

```rb
 p ninja_turtle[:pizza_toppings][0]
```

Produce an array containing all of `ninja_turtle`'s keys using a method. [The Ruby documentation might help](http://ruby-doc.org/core-1.9.3/Hash.html).

```rb
 p ninja_turtle.keys```

#### Bonus

Print out each key-value pair in the following format - "KEY's is equal to VALUE" -- using a method. [The Ruby documentation might help](http://ruby-doc.org/core-1.9.3/Hash.html).

```rb
# Your answer here
```
