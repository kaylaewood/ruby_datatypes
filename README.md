# Ruby Methods (in Comparison to JS)

This is a collection of exercises created by Turing School of Software & Design to practice various data types in Ruby including **strings**, **integers**, **floats**, and **arrays**.

## View the Methods in Action with Testing:
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
|`str.reverse` or `arr.reverse`|Reverses the order of all elements in a string or array.|`str.split('').reverse().join('')`|
|`str.gsub(old, new)`|Replace part of a string with something new.|`str.replace(old, new)`|
|`str.length` or `arr.length`|Count the number of characters in a string or elements in an array.|`str.length` or `arr.length`|
|`str.count(substr)`|Count the number of occurences for one or multiple substrings in a larger string.|N/A (Would need a counter and loop)|
|`str.include?(substr)` or `arr.include?(elem)`|Check to see if a string includes a substring or an array incldues an element.|`str.includes(str)` or `arr.includes(elem)`|
|`str.concat(diffstr)`|Combine multiple strings into one string.|`str.concat(str)`|
|`int.fdiv(diffint)`|Divide two integers with a resulting decimal.|`int / diffint`|
|`int.even?`|Results in a boolean stating whether an integer is even.|N/A (Would need to use a modulus and conditional logic)|
|`int.round()`|Round to the nearest whole number. You can add a number inside the parens to indicate the place value you want to round to.|`Math.round(int)`|
|`int.ceil`|Round up to the next whole number.|N/A|
|`arr.last`|Return the last item in an array.|`arr[arr.length - 1]`|
|`arr.push(elem)` or `arr << str`|Add an element to the end of an array.|`arr.push(elem)`|
|`arr.pop`|Remove and return last element from array.|`arr.pop()`|
|`arr.unshift(elem)`|Add element to beginning of array.|`arr.unshift(elem)`|
|`arr.shift`|Remove and return first item in array.|`arr.shift()`|
|`arr[n..length]`|Return a subarray starting at index `n` of given length.|N/A (Would have to iterate with conditionals)|
|`arr.delete(elem)`|Delete all items in the array that are equal to the element provided.|`arr.filter(elem => elem !== elemToFind)`|
|`arr.flatten`|Remove nested arrays.|`arr.flat()`|
|`arr.rotate! n`|Rotate the elements `n` spots.|N/A|
|`arr.insert(index, elem)`|Insert an element at the given index.|`arr.splice(start, deleteNum, itemsToAdd)`|
|`arr.join(str)`|Combine all elements of an array with given string in between.|`arr.join(str)`|
  
## Sources
  * [Turing Ruby Datatypes Lesson](https://backend.turing.io/module1/lessons/datatypes)
  * [Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
  * [Ruby Tutorial](https://teamtreehouse.com/library/ruby-collections)
  * [Ruby Help](https://apidock.com/ruby)
  * [Ruby Cheatsheet](https://www.shortcutfoo.com/app/dojos/ruby-arrays/cheatsheet)
 
