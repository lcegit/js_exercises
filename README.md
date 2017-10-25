## Javascript Exercises #1
**Basic stuff!**

1. Create an array and add three numbers to it.
```
var newArray = [1, 5, 3.22, 5, 54.3, 42.e4, 53.9743]
```

2. Use your array to return the second number.
```
numbers[3]
```

3. a. What data type is 123/12? b. "Things in quotes!"? c. undefined?
```
a. Number b. String c. undefined
```
4. Write an if statement that returns true.
```
var myVar = "Lisa";
if (myVar === "Lisa") {
    true;
  //  console.log("That's my name");
} else {
   false;
//   console.log("That's not me");
}
```

5. Consider these two arrays: myArray = ['Thomas', 'Amber', 'Raoul'] and emptyArray = []. Use a for loop to add our names to emptyArray. (Hint: n needs to be the length of the array. Google a helper method for finding the length of an array in Javascript. Is it the same as Ruby?)
```
myArray = ['Thomas', 'Amber', 'Raoul']
emptyArray = []
myArray.forEach(function(myArray) {
  emptyArray.push(myArray);
});
```
## Javascript Exercises #2

1. Write a function that returns your first name. Call it.

```
function firstName() {
  return "Lisa";
}
firstName();
```
2. Write a new function that takes your name as an input. The function should return your first name, plus your last name, as one string.

```
function elName (firstName) {
  var lastName = "Eriksson"
  return firstName + " " + lastName;
}
console.log(elName('Lisa', 'Eriksson'));
```
## Javascript Exercises #3

1. What is `.this`? Does it have an equivalent in Ruby?

`this.` assigns a variable within a function / "constructor". It's the equivalent of the initialize method in Ruby.
