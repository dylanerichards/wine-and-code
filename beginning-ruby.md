# NYCDA Wine and Code

## Fix Tac Toe: Learn the Basics of Ruby

### Setup
1. [Install Ruby](http://www.railsinstaller.org/en)
2. [Install Sublime Text](http://www.sublimetext.com)
3. [Download the broken Tic Tac Toe game](https://github.com/dylanerichards/fix-tac-toe)

And we're *ready to roll.* ;)

## Topics
### Data Types and Structures
* Strings
* Variables
* Arrays
* Hashes
* Functions

#### Control Flow
* if/else
* case

#### Object Orientation
* Objects
* Constructor function
* Attributes
* Readers and writers

## Exercises

### Strings

* Assign a variable `greeting` to a string message, like `"Hello!"`.
* Assign a variable `name` to some name.
* Take that greeting and concatenate a name to the end of it, so it reads something like `"Hello, Justin!"`.

### Arrays

* Make an array with 5 fruits in it, represented as strings.
* Access the first element of the array.
* Access the last element of the array.
* Access the second-to-last element of the array, starting from the last element.
* Reverse the order of this array.
* Iterate over each element in this array and output each fruit name reversed.

### Control Flow

* Iterate over each element in the fruits array, but only output the reversed name if it contains the letter "e". If it does not contain the letter "e", then just output the original name of the fruit.

### Hashes

* Create a hash with fruit names as keys. Values should be either "yes" or "no", indicating whether or not the fruit is a favorite of yours.
* Return an array of all of the keys in the hash.
* Return an array of all of the values in the hash.
* Iterate over this hash, returning only the favorite fruits.

### Functions
* Write a `greeting` function that returns `"Hello, Justin!"`
* Allow the function to accept a `name` argument, and interpolate that name into the return value of the greeting.
* Write a function that returns the sum of two numbers, both passed in as arguments.

### Object Orientation
* Make a `Thing` class.
* Create a new instance of `Thing` and assign it to a variable, say `thing`.
* Add a `name` attribute to `Thing`. *(don't forget to add the argument to the initialize function)*
* Create another instance of `Thing`, but give it a name this time.
* Call `thing.name`. What happens?
* Create a new `Student` class. Give it a `name` and an `age`.
* Create some `Student` instances.
* Create a new `School` class. Add a `students` attribute. It should be an array.
* Add the students to the School's `students` array.
* Define a method on `Student` that returns its age in 20 years.
* Iterate over the School's students collection and return each student's age in 20 years.

### Tic Tac Toe
#### `board.rb`
* `WINNING_COMBINATIONS` represents the places on the Tic Tac Toe board that must be occupied in order for there to be a winner. Fill in the remaining ones.
* The call to `Array.new()` in the `initialize function is missing an argument. It should be an integer equal to the number of spaces on a Tic Tac Toe board. Pass in the correct argument.
* The keys in the `POSITIONS` hash represent what the user will need to type in to place his/her piece on the board. The values represent where the piece will go. Fill in the remaining key/value pairs.

#### `tic_tac_toe.rb`
* Complete the case statement beginning on `line 17`. If the user picks "X", then the computer should be "O", and vice versa. If the user picks neither "X" nor "O", then assign `@computer` to a string of your choice.