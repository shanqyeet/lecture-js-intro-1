# Introduction to Javascript
+++
### It is not Java
![](http://www.codingdojo.com/blog/wp-content/uploads/javascript.jpg)
+++
### It's...
* Client-side scripting language
* Developed by Brendan Eich in 1995
* Can be run on any operating systems and almost all web browsers

+++
### What does Javascript do? 
1. Add interactivity to your page, i.e. allow your website to respond to user event
2. Change page contents dynamically
3. Control your browsers
4. Create Cookies 
5. Help send and receive data to web servers 
and more...
+++
### Example websites with pure JS
1. [The Boat](https://www.sbs.com.au/theboat/)
2. [Filippobello](http://www.filippobello.com/portfolio)
3. [Histography](http://www.histography.io/)
---

# What you will learn today
+++
### Link the script to your HTML
```html
<body>
    <script src="scripts.js"></script>
</body>
```
+++
### Some basics
1. **Integer**: 1, 2, 3, 10, 11
2. **Float**: 1.123, 10.2, 11.99
3. **Variables**: like a storage, i.e. const name = "Edwin"
4. **String**: "This is a string"
5. **Boolean**: true / false 
6. **Function**: reusable block of codes
7. **Array**: [1,2,3,"a","b","c"]

+++
### Arithmetic Operator with Numbers 
* Addition:  + 
* Subtraction: -
* Multiplication: *
* Division: /
* Remainder: %
* Increment: ++ 
* Decrement: --
+++

### Variables
```js
const myName = "Shanq Yeet" //-> values cannot be changed

myName = "Edwin" //-> Will get error

let myAge = 18 //-> values can be changed

myAge = 21 //-> myAge will be updated to 21
```
+++
### Variables 
Naming of Js variables should always follow camelCase, i.e.
1. myAge
2. myScores
3. myListOfQualifications
+++

### String
1. "can be in double quote"
2. 'can be in single quote'

Either way it is a bunch of text with available functions to help you access and manipulate its values

+++
### Boolean - Comparator 2 
```js
1 == 2 // false 

1 < 2 // true 

1 > 2 // false 

1 != 2 // true 

1 =< 2 // true 
```
+++
### Boolean - Comparator 2
```js
1 == 2 || 2 == 2 // you get true because one of it is true 

1 == 2 && 2 == 2 // you get false because you need both to be true 
```
+++
### Function - Declare
```js
function addition(x, y) {
    return x + y
}
```
+++

### Function - Use
```js
addition(1,2) //-> you get 3 
```
When you go through the material, Pay attention to **Function Scope**
+++

### Function - Importance of 'return'
```js
function addition(x, y) {
    x + y
}

addition(1,2) //-> you get nothing 
```
+++
### Array
![](https://sc02.alicdn.com/kf/HTB1o.ovSFXXXXawXVXXq6xXFXXXg/202391929/HTB1o.ovSFXXXXawXVXXq6xXFXXXg.jpg)
+++
### Array - Extracting Data with Index
![](http://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-Array-Find-indexOf-Method-Example.png)

There are also a bunch of functions available to access and manipulate array data
