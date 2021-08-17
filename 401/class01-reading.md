# Readings: Node Ecosystem, TDD, CI/CD

## Describe (in plain English) what Array.map() does

Map is a method that you can call on an array that takes a callback function. The callback function takes one argument and must return something. Every item in the array will be passed as a parameter to this callback function, and map will return the new array that is created as a result of this operation.

## Describe (in plain English) what Array.reduce() does

Reduce is an array method that is useful for combining in some way the contents of an array. It takes a callback function with two arguments, an aggregator and the current item. The value of the aggregator changes based on how you modify it with each individual item. The final value of the aggregator will be returned by array.reduce().

## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
#### With normal Promise .then() syntax:

``superagent.get(url).then((data)=>{console.log(data)});``


#### Again with async / await syntax

```
  try{
    const response = await superagent.get(url);
    console.log(response);
    }
  catch(err){
      console.log(err)
      }
```

## Explain promises as though you were mentoring a Code 301 level student

Promises are one way we can handle asynchronous operations in javascript. When you create a promise it will give you access to the .then method, which itself contains a callback with the relevant data as an argument. 

## Are all callback functions considered to be Asynchronous? Why or Why Not?

They can be, but they can also not be.
