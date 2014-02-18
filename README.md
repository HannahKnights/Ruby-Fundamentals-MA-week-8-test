Ruby Revision
========

### Friday test

[Makers Academy](http://www.makersacademy.com) traditional Friday test. This will be testing the basics of Ruby, the building blocks of the course. Here is the premise:

There are 41 questions - you don't have to do every single one (although if you can, that's great). You should be able to do at least 50% of them. They vary in level from quite easy to fairly hard. Work through them and check if they're correct by running the specs.

You should be able to answer most questions with a couple of lines of code, and just a few methods. If you're writing a long, complex solution, there's probably a better way.

To run the specs:

~~~
$ rspec questions_spec.rb
~~~

**Quick tip**: to run a single example, change `it` to `fit` on that example, then run

~~~
$ rspec questions_spec.rb --tag focus
~~~

Try and do the bulk of these in one day.

### Rules

* Try and get the RSpec tests to pass (but not by cheating - i.e. hardcoding the expected value)
* You shouldn't need any extra libraries or gems
* The cleaner your code the better!
* Googling is fine as usual

### Tips

* Use the ruby docs http://www.ruby-doc.org/core-2.0.0/String.html
* Try and break down the problems into smaller chunks. For e.g. if you google "How to select elements in an array that start with a", you won't have much luck. Try and find out a) how to select certain elements in an array, b) how to test if a string starts with an 'a'
* Don't forget Enumerable (advanced array methods)
* Read the specs and the comments - if you're still confused, just ask.
* Don't panic :wink:
