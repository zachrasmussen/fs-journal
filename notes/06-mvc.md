# MVC
7/27 - morning challenge

Write a function that will take in one argument, a string. Determine if the given string is a palindrome, and return either true or false. (A palindrome is a word that's spelled the same both forward and backward.) For this exercise let's not worry about space characters.

// Examples
  // 'taco cat' => true
  // 'kayak' => true 
  // 'hello' => false | 'aibohphobia' (the fear of palindromes)
  // Output: true      | true    | false   | true

function isPalindrome(str) {
  for(let i = 0; i < Math.floor(str.length / 2); i++) {
    console.log(str[i], str[str.length - 1 - i])
    if(str[i] !== str[str.length - 1 - i]) {
        return false
    }
  }
return true
}



function reverseCheck(str) 
[
    return str == str.split('').reverse().join('')
]

if arr = reversed
return true






if arr = reversed
return true

kayak == kayak

let kayak = ['k','a','y','a','k'];
let length = kayak.length;

let kayak[0] = kayak[4]
let kayak[1] = kayak[3]
let kayak[2] = kayak[2]

if word frontwards && word backwords == true

if (word = word backwards) {
return true
}
else {
    return false
}


<!-- NOTE Morning Challenge 8/2 -->
Write a function that takes in a single str and return the most frequently occurring letter within that string

//example:
  // mostCommonLetter('hello') => 'l'
  function mostCommonLetter(str) {
  //your code here
}

let str = 'mostCommonLetter'

function mostCommonLetter(str) {
  let alphabet = {}

  for(let i = 0; i < str.length; i++) {
   let letter = str[i]
   alphabet[letter]
if(alphabet[letter]){
  alphabet[letter] ++
} else{
  alphabet[letter] = 1
  }
  
}

return alphabet

}

<!-- NOTE Morning Challenge 8/3 -->

Create a function that takes a number as its argument and returns an array of all its factors.

// Examples:
// factorize(12) ➞ [1, 2, 3, 4, 6, 12]
// factorize(4) ➞ [1, 2, 4]
// factorize(17) ➞ [1, 17]
function factorize(n) {

}

function factorize(n) {
  let factors = []
  for (let i = 1; i <= n; i++) {
    if(n % i == 0){
      factors.push(i)
    }
  }
return factors
}



 