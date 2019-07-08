# Solutions

## Multiply

```JavaScript
function multiply(a, b){
  return a * b;
}
```

## Function 1 - hello world

```JavaScript
// Write a function "greet" that returns "hello world!"
function greet (){
  return 'hello world!';
}
```

## Remove First and Last Character

```JavaScript
function removeChar(str){
  let str1 = ''; //ppl
  for (let i = 1; i < str.length - 1; i++){
  str1 +=str[i];
}
return str1;
}
```

## Capitalization and Mutability

```JavaScript
function capitalizeWord(word) {
 let wordNew = word[0].toUpperCase();
  
  for (i = 1; i < word.length; i++){
  wordNew += word[i];
  }
  return wordNew;
}
```

## Will you make it?

```JavaScript
function zeroFuel(s, mpg, g){
 return (s <= mpg * g);
 }
 ```

 ## Opposite number

```JavaScript
function opposite(number) {
  return -number
}
```

## If you can't sleep, just count sheep!!
```JavaScript
var countSheep = function (num){
  let str = "";
  for (let i = 1; i <= num; i++) {
    str = str + i + " sheep..."
  }
  return str;
}
```

## Get list sum recursively

```JavaScript
function sumR(x) {
  if (x.length === 0) {
    return 0;
  }
  return x[0] + sumR(x.slice(1));
}
```

## When provided with a number between 0-9, return it in words.

```JavaScript
function switchItUp(number){
let arr = ['Zero', 'One', 'Two', 'Three', 'Four','Five', 'Six', 'Seven', 'Eight', 'Nine'];
return arr[number]
}
```
## Convert a string to an array

```javascript
function stringToArray(string){
  let arr = [];
  let word = '';
  for (let i = 0; i < string.length; i++) {
    if (string[i] === ' ') {
      arr.push(word);
      word = '';
    } else {
      word += string[i];
    }
  }
  arr.push(word);
  return arr;
}
```

## Determine offspring sex based on genes XX and XY chromosomes

```JavaScript
function chromosomeCheck(sperm) {
  if (sperm === 'XY') {
    return "Congratulations! You're going to have a son.";
  }
  if (sperm === 'XX') {
    return "Congratulations! You're going to have a daughter.";
  }
  return "Sorry, You will have an alien!";
}
```

## Thinkful - Logic Drills: Traffic light

```JavaScript
function updateLight(current) {
  switch (current) {
    case "green":
      return "yellow";
    case "yellow":
      return "red";
    case "red":
      return "green";
    default:
      return "black";
  }
}
```

## The Feast of Many Beasts

```JavaScript
function feast(beast, dish) {
  return beast[0] === dish[0] && beast[beast.length-1] === dish[dish.length-1];
}
```

## Simple multiplication
```JavaScript
function simpleMultiplication(number) {
  if (number % 2 === 0) {
    return number * 8;
  } else {
    return number * 9;
  }
}
```

## Student's Final Grade

```JavaScript
function finalGrade (exam, projects) {
 if (exam > 90 || projects > 10) {
   return 100;
 }
 if (exam > 75 && projects >= 5) {
   return 90;
 }
 if (exam > 50 && projects >= 2) {
   return 75;
 }
 return 0;
}
```
