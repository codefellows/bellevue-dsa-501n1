![cf](http://i.imgur.com/7v5ASc8.png) 01: Basic Data Structures
===

## Learning Objectives
	
* Why do algorithms matter?
* Computer science is a way of thinking, not things to know. 
* Students will learn computer architecture
* Students will learn the Layers of Abstraction
* Students will cover complexity analysis && big O notation
* Students will learn data abstractions and assumptions
* Students will learn formal definitions
* Sudents will learn how to improve run time?
* Students will go over Three-Sum problem
* Students will learn how to delete duplicates
* Students will learn basic data structures
 
## Data Structures 

* Strings
    * [what’s a word in what language :)] length of last word
    * palindrome
* Lists
* Arrays - contiguous [a, b, c, d]
* Hash tables

## Homework

* Phone Number
* Implement even-odd merge
* Print spiral traversal of 2D array
* Sort array into a wave pattern
* Merge intervals

## Whiteboarding

* **Mock Whiteboard** - Vishal & Brook will interview each other and demonstrate a mock whiteboarding interview.
    * **Question:** Find the smallest positive missing number in an array that contains both positive and negative integers

* **Mock Whiteboard** - Students will do mock whiteboarding interviews 
    * **Question:** Implement Run-Length Encoding 
aaaabcccaa => 4a1b3c2a
3e4f2e	=> eeeffffee

### bubbleSort
```javascript
const bubbleSort = (a) => {
    for(let i = 0; i < a.length; i++){ // N
        for(let j = 0; j < a.length - i - 1; j++){ // N^2
            if(a[j] > a[j + 1]){ // this if statement is constant
                let temp = a[j];
                a[j] = a[j +1];
                a[j + 1] = temp;
            }
        }
    }
}
// big O - O(n^2) because we have nested loops
```
