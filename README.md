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

 ## Refactor

Opposite number
JavaScript:
function opposite(number) {
  return -number
}