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

## Type of sum

```JavaScript
function typeOfSum(a, b) {
  return typeof (a + b);
}
```
## Sleigh Authentication

```JavaScript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
  if (name === "Santa Claus" && password === "Ho Ho Ho!") {
  return true;
  } else {
  return false;
  }
};
```

## Switch it Up!

```JavaScript
function switchItUp(number){
  let arr = ['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine'];
  return arr[number];
}
```

## Random case

```JavaScript
function randomCase(x) {
  let str = '';
  for (let i = 0; i < x.length; i++) {
    if (Math.random() > 0.5) {
      str += x[i].toLowerCase();
    } else {
      str += x[i].toUpperCase();
    }
  }
  return str;
}
```

## Alphabet symmetry

```JavaScript
function solve(arr){  
  let res = [];
  const codeA = 'a'.charCodeAt(0);
  for (let w = 0; w < arr.length; w++) {
    let word = arr[w];
    let cnt = 0;
    for (let i = 0; i < word.length; i++) {
      let char = word[i].toLowerCase();
      if (char.charCodeAt(0) === codeA + i) {
        cnt++;
      }
    }
    res.push(cnt)
  }
  return res;
};
```

## Credit card issuer checking

```JavaScript
function getIssuer(number) {
    let s = '' + number
    let f1 = s.substr(0, 1);
    let f2 = s.substr(0, 2);
    let f4 = s.substr(0, 4);
    if ((f2 === "34" || f2 === "37") && s.length === 15) {
        return "AMEX";
    }
    if (f4 === "6011" && s.length === 16) {
        return "Discover";
    }
    if (["51", "52", "53", "54", "55"].indexOf(f2) >= 0 && s.length === 16) {
        return "Mastercard";
    }
    if (f1 === "4" && (s.length === 13 || s.length === 16)) {
        return "VISA";
    }
    return "Unknown";
}
```

## Create Phone Number

```JavaScript
function createPhoneNumber(numbers){
  let s = numbers.join('');
  return `(${s.substr(0, 3)}) ${s.substr(3, 3)}-${s.substr(6)}`
}
```

## Remove String Spaces

```JavaScript
function noSpace(x){
  return x.replace(/ /g, "");
}
```

## Who is going to pay for the wall?

```JavaScript
function whoIsPaying(name){
  if (name.length > 2) {
    return [name, name.substr(0,2)]
  }
  return [name]
}
```

## Do I get a bonus?

```JavaScript
function bonusTime(salary, bonus) {
  return "\u00A3" + (bonus ?  salary * 10 : salary);
}
```

## Returning Strings

```JavaScript
function greet(name){
  return `Hello, ${name} how are you doing today?`;
}
```


