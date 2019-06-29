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

## new solution

