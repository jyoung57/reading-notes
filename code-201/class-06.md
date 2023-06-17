> # Read Clas 06

## JavaScript Object Basic

1. How would you describe an object to a non-technical friend you grew up with?

- An object is a collection of related data or functionality. Objects have three characteristics: State, Behavoir, Identity.

2. What are some advantages to creating object literals?

- An object literal in JavaScript allows us to create plain JavaScript objects. It consists of a list of key-value pairs, each separated by a comma and wrapped inside curly braces.

3. How do objects differ from arrays?

- An object literal in JavaScript allows us to create plain JavaScript objects. It consists of a list of key-value pairs, each separated by a comma and wrapped inside curly braces.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- If an object property name is held in a variable, then you can not use dot noation and bracket notation is required.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

```css
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

- "This" executes the current piece of coding.

## Introduction to DOM

1. What is the DOM?

- The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.

2. Briefly describe the relationship between the DOM and JavaScript.

- DOM is what makes your webpages function, while JS is what allows you to make the web pages do what you want them to do. Without DOM, JS wont work.

## > Things I Want to Know More About