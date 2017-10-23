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
a. Number b. String c. undefined

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
for(var n = 0; n < myArray.length; n++) {
  emptyArray.push(myArray[n]);
}
```
