# day3
🥲🥲🥲🥲🥲
# For the given JSON iterate over all for loops (for, for in, for of, forEach)
 # for loop:
Initialization - initialize the loop variable with a value and it is executed once
Condition - defines the loop stop condition
Update - executed every time after the code block of the loop has been executed.
*example:
var array = [
    {id: 0, name: 'John', age: 20},
    {id: 1, name: 'Jane', age: 22},
    {id: 2, name: 'Bob', age: 24},
    {id: 3, name: 'Ana', age: 26},
];

for(let i = 0; i < array.length; i++){
    console.log(array[i].name);
}

# for of loop:
Iterator - refers to the array who will be iterated
Variable - The value of the next iteration stored in a variable (which has to be declared with either const, let, or var to hold the value)
*example:
var array = [
    {id: 0, name: 'John', age: 20},
    {id: 1, name: 'Jane', age: 22},
    {id: 2, name: 'Bob', age: 24},
    {id: 3, name: 'Ana', age: 26},
];

for (let index of array) {
    console.log(index.name)
}

# for each:
currentValue - value of the current element
index (optional) - array index of the current element
array (optional) - entire array object
The thisArg (optional) - value for the callback function which will be used as its this value.
*example:
var array = [
    {id: 0, name: 'John', age: 20},
    {id: 1, name: 'Jane', age: 22},
    {id: 2, name: 'Bob', age: 24},
    {id: 3, name: 'Ana', age: 26},
];

array.forEach(function(profile, index, myArray) {
    console.log(`Index: ${index}, Name: ${profile.name}`);
});

# for in:


