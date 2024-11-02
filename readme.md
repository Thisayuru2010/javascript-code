# My coding experience with js
My javascript coding experiense
It is a long journey ahead.I just learned coding and entered the self learning stage
I am 14 and I am solving simple problems now.here ar some
date=2024/11/1
# SOLUTIONS FOR PROGRAMING TASKS

- **Prime Number Checker:** Develop a function that determines whether a given number is prime or not.

prime number problem solved

```jsx
let numb = prompt('enter prime number')
let num = Number(numb);
if (num <= 1){
  console.log('this is not a prime number')
}
for(let i = 2 ; i <= Math.sqrt(num);i ++){
  if (num % i ===0 ){
    console.log('this is not a prime number');
  }
}
console.log('this is a prime number')
```

**Odd or Even Checker**

Write a function that checks if a number is odd or even.

**Example:**

- Input: `4`
- Output: `Even`

Odd or even checker solved

```jsx
let numbe = prompt('enter your number')
let num= Number(numbe)
if (num % 2 === 0 );
  console.log('this is a even number')
console.log ('this is a odd number')
```

### 2. **Sum of Numbers**

Write a program that calculates the sum of all numbers from 1 to a given number 

sum of number solved

```jsx
let numb = prompt('enter the number')
let n = Number(numb)
  let sum = 0;
  
  for (let i = 1; i <= n; i++) {
    sum += i; 
  }
  console.log(sum)
```

REVERSING STRINGS

GETING INPUT AND REVERSING IT (STRING)

```jsx
let str =  prompt('input your string');
let reverse = str.split('').reverse().join('');
console.log(reverse);
```

**Factorial of a Number**

Write a function that computes the factorial of a number. The factorial of a number `n` is the product of all positive integers less than or equal to `n`.

```jsx
let num = prompt('write a number');
let number = Number(num);
let sum = 1;
for (let i = 1; i <= number; i++) 
  sum *= i;
  console.log (sum); 
```

### 6. **Palindrome Checker**

Write a function that checks whether a given string is a palindrome (a string that reads the same forwards and backwards).

**Example:**

- Input: `"madam"`
- Output: `true`

```jsx
let word = prompt("Enter a palindrome word");
if (word === word.split("").reverse().join("")) {
  console.log(word + " is a palindrome word");
} else {
  console.log(word + " is not a palindrome word");
}
```

**Count Vowels in a String**

Write a function that counts the number of vowels (a, e, i, o, u) in a given string.

**Example:**

- Input: `"hello"`
- Output: `2`

```csharp
let word = prompt("Enter a word: ");
let vowels = ["a", "e", "i", "o", "u"];
let count = 0;

for (let yes = 0; yes < word.length; yes++) {
    if (vowels.includes(word[yes])) {
        count++;  
    }
}
console.log(count);
```

### 9. **Multiplication Table**

Write a program that prints the multiplication table for a given number.

**Example:**

- Input: `5`
- Output:

```jsx
let num = prompt('Enter a number');
let number = Number(num);
for (let i = 1; i <= 10; i++) {
    console.log(`${number} * ${i} = ${number * i}`);
}
```
Now coding is getting harder to me .I am learning .commands now.I know Its gettting harder till i be at a scertain point.
10. **Find the Second Largest Number in an Array**

Write a function that finds the second largest number in an array.

**Example:**

- Input: `[3, 5, 7, 2, 8]`
- Output: `7`

let arr = prompt("Enter the array");
if (arr.length <= 2) {
    console.log("enter a array with more numbers");
}
```jsx
let arr = prompt("Enter the array");
if (arr.length <= 2) {
    console.log("enter a array with more numbers");
}
let first = -Infinity;
let second = -Infinity;
for (let i = 0; i < arr.length; i++) {
    if (arr[i] > first) {
        second = first;
        second = arr[i];
    } else if (arr[i] > second) {
        second = arr[i];
    }
}
console.log(second);

