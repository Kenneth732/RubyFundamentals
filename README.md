# Everything in ruby is an Object
try: "Hello world".class()

We just called a method on "Hello world!" Method is just another term for a function that is called on an object. In JavaScript, we often call these functions. In Ruby, we call them methods because everything is an object and all functions are called on objects. All methods are functions, but the reverse isn't necessarily true.

"Hello world!" is an instance of the class String. We can make a string in Ruby by enclosing a sequence of characters in either single or double quotation marks. These characters can include letters, numbers and symbols.

# All objects are instances of a class.
In fact, classes are objects, too. Ruby has a number of commonly used classes; String is one of them. We'll be covering a number of other classes in the next few lessons in addition to String, including Array, Number, Float, Range and Hash. Most of these classes (such as String and Number) are already familiar to you from JavaScript.

# Let try another EX:
"Hello world!".methods()
length() returns the total number of characters in the string. reverse() reverses the string. And concat() works just as it does in JavaScript: it concatenates two strings together.

In the last example, we passed an argument to concat(), just as we passed arguments into functions in JavaScript.

# Number and Float
5.even?()
5.next()
 5.positive?()

 5.methods()

 # Float is quite similar to Number. It's really just another word for decimal.
 5.3.class()
 
 5.3.round()
 
 8.1.ceil()
 
 # Chaining Methods
5.3.round().next()

5.3.ceil().next()


# Array
["a", "b", "c"].length()

[1, 2, 3].shuffle()

[1, 2, 3].push(4)

# Here are a few methods for returning a specific element from an array:

[1,2,3].first
[1,2,3].last
[1,2,3][1]
[1,2,3].at(1)

# Ranges
(1..10)

Ranges have many methods, too. Here are a few:

(1..10).size()

("a".."z").end()

