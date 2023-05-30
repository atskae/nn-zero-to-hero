# [Makemore](https://www.youtube.com/watch?v=PaCmpygFfXo&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2)

**Makemore** is a character-level language model.
* It generates more things that are similar to its input data
* Predicts the next *character* in the sequence
* [`names.txt`](https://github.com/karpathy/makemore)

`5:27` A single word in a dataset gives us many pieces of information:
* `isabella`
  * `i` is likely to be a first character
  * `s` is likely to come after `i`
  * `a` is likely to come after `is`
  * `b` is likely to come after `isa`
  * ...
  * `a` is likely to come after `isabell`
  * The word `isabella` is likely to be a full word (no letter comes after `isabella`)

`5:51` Building a **bigram** language model, which looks at only two characters at a time
* We look at the character we are looking at, and want to predict the next character
* We only look at just that local structure
