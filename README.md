# Ruby Data Type Exercises

This is a collection of exercises created by Turing School of Software & Design to practice various data types in Ruby including strings, integers, floats, collections, and arrays.

## Setup
1. `clone` this repo.
2. `cd` into this directory.
3. Run `bundle`.
4. To run tests, `cd` into the appropriate directory (i.e. `strings`) and run `ruby [file name]` (i.e. `strings.rb`).
  
## Methods I Learned/Used:
|Method|Explanation|JS Equivalent|
|---|---|---|
|`str.capitalize`|Capitalizes the first letter of a string.|`str.replace(/^\w/, char => char.toUpperCase())`|
|`str.upcase`|Capitalizes all letters in a string.|`str.toUpperCase()`|
|`str.downcase`|Makes all letters in a string lowercase.|`str.toLowerCase()`|
|`str.reverse`|Reverses the order of all elements in a string.|`str.split('').reverse().join('')`|
|`str.gsub(old, new)`|Replace part of a string with something new.|`str.replace(old, new)`|
|`str.length`|Count the number of elements in a string.|`str.length`|
|`str.count(substr)`|Count the number of occurences for one or multiple substrings in a larger string.|N/A (Would need a counter and loop)|
|`str.include? [substr]`|Check to see if a string includes a substring.|`str.includes(str)`|
|`str.concat(diffstr)`|Combine multiple strings into one string.|`str.concat(str)`|
|`int.fdiv(diffint)`|Divide two integers with a resulting decimal.|`int / diffint`|
|`int.even?`|Results in a boolean stating whether an integer is even.|N/A (Would need to use a modulus and conditional logic)|
|`int.round()`|Round to the nearest whole number. You can add a number inside the parens to indicate the place value you want to round to.|`Math.round(int)`|
|`int.ceil`|Round up to the next whole number.|N/A|
||||
  
## Sources
  * [Strings Video Walk-Through](https://youtu.be/BKqo2w0W7S0) by Turing
  * [Collections/Arrays Video Walk-Through](https://youtu.be/RUnd1Uu0AyE) by Turing
  * [Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
  * [Ruby Datatypes Lesson](https://backend.turing.io/module1/lessons/datatypes) by Turing
  * [gsub Guide](https://www.rubyguides.com/2019/07/ruby-gsub-method/)
  
