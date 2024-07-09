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

##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/6593e0bc-0433-49dc-90a0-db3e32fdbd27)
##### ![image](https://github.com/dbnaveen/JavaScript-Questions-2024/assets/15210898/bacb81fa-c7c9-44c6-8b19-93cd0cfd3cf1)





