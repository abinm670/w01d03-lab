# functions

#### Exercise 1:
Write a JavaScript function that returns a passed string with letters in alphabetical order.
Example string: 'Sara'
Expected Output: 'araS':

```
function alphabetOrder(name)
{
   //Use the split() method to return a new array
   //Use the reverse() method to reverse the new created array
   //Use the join() method to join all elements of the array into a string
    return name.split("").reverse().join("");
}

x=alphabetOrder("hello");
console.log(x);

```
---
#### Exercise 2:
Write a JavaScript function that reverse a number.
Sample Data and output:
Example x = 12345;
Expected Output: 54321

```

function reverseANumber(n)
{
    n = n + "";
	return n.split("").reverse().join("");
}


reverseANumber(987654321);
```
---
#### Exercise 3:
Write a JavaScript function that accepts a number as a parameter and check the number is prime or not.
Note : A prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

```
const isPrime = num => {
    for(let i = 2; i < num; i++)
      if(num % i === 0) return "Not a prime number";
    return "prime Number";
  }

  console.log(isPrime(3))

```
---

#### Exercise 4:
Write a JavaScript function that accepts a number as a parameter and check the number is prime or not.
Note : A prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

```


testPrime(37);
```
#### Exercise 5:
Write a JavaScript program to pass a 'JavaScript function' as parameter.

```
function addStudent(id, yesTes)
{
    yesTes()
    {
         console.log("test " + id)
    } 
}

function go() {
    console.log('Happy Coding');
}

addStudent(2, go);
```
---
#### Exercise 6:
Write a JavaScript program to pass a 'JavaScript function' as parameter.

Write a function that takes the base and height of a triangle and return its area.
Examples
function triArea(num1, num2)
{
    return (num1*num2)/2; 
}

triArea(3, 2) ➞ 3

---
#### Exercise 7:
Write a function that takes an integer minutes and converts it to seconds.

```
function convert(min)
{
    return min*60

}
convert(2);
```
---

