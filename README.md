##### Q1: Explain Debouncing? [Link](https://codesandbox.io/p/sandbox/debouncing-js-4nqknj?file=%2Fsrc%2Findex.html)

###### Debouncing is a technique used to ensure that the function is executed once after a certain delay, even when it is called multiple times. Used for performance optimisation.


##### Q2: Sort the sentence as per the position [Link](https://codesandbox.io/p/sandbox/sort-as-per-sentence-t2j39w?file=%2Fsrc%2Findex.mjs)
```js
@Input- "is2 sentence4 This1 a3"
@Output- "This is a sentence"
```

##### Q3: What is the output of the code below
```js
const arr = [{}, '2', 'hello']
delete arr[1]
console.log('arr', arr.length) //3
```

###### It removes the element but leaves the empty slot in the array. If you want to remove the element and update its length, use methods like `splice`
<img width="597" alt="image" src="https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/8bcfce18-7736-4718-8690-f31e93567eb9">

##### Q4: Explain splice methods
###### It is used to add, remove or replace items in an array
```js
const arr = [1, '2', 'hello']

//@add 
arr.splice(0, 0, 'world') //['world', 1, '2', 'hello']
//@remove
arr.splice(1, 2) //[1]
//@replace
arr.splice(2, 1, 'new') //[1, '2', 'new']
```

##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/ddea4835-2e5f-404d-8cb9-285722f6cd13)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/19d77920-b534-4b52-b46e-01238617ac1e)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/91372f5e-b749-4f21-9962-331180e3593d)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/106b0c58-7f47-43fa-af8a-faea21a2816a)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/5013a82a-8399-46a9-9760-cca14483ce43)[Link](https://codesandbox.io/p/sandbox/timer-pdghcl?file=%2Fsrc%2Findex.html)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/8c2e5999-f340-4cc0-8bdf-c637d791d11c)












