> # Reading Class 03

> ## Learning HTML

1. When should you use an unordered list in your HTML document?

- When you are wanting to display a bulleted list.

2. How do you change the bullet style of unordered list items?

- You can next a <ul> element that will indent the bullet. Or use a list-style-type.

3. When should you use an ordered list vs an unorder list in your HTML document?

- If you list is meaningful, you should use an <ol> element.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

- The use of type-start or a combination of nesting with ul or ol.

> ## Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

- I am margin. I am the invisible space around your box. I can push other elements away from your box.

* I am padding. I create white space around the content. I can be adjusted to your liking.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

-

> ## Learn JS

1. What data types can you store inside of an Array?

- Strings, numbers, objects, boolean values, other arrays, etc.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```js
const people = [
  ['pete', 32, 'librarian', null],
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'],
  ['bill', null, 'artist', null],
];
```

- This is a valid array. We have a valid data type of a string and null values. It repeats throughout the array. You can access the values stored by using index of the people array and then the index of the first index. This can be done with console.log(people[0]) or by assigning the index array value to a variable, then indexing that variable.

3. List five shorthand operators for assignment in javascript and describe what they do.

- x += f() sets the value of x = x + f
- x /= f() sets the value of x = x / f
- x && = f() it determines if x and f are equal to a value that in not undefined or null.
- x = f() sets the value of x = f
- x _= f() sets the value of x = x _ f

4. Read the code below and evaluate the last expression and explain what the result would be and why.

```js
let a = 10;
let b = 'dog';
let c = false;

// evaluate this
a + c + b;
```

- The result will be 10dog. The expression is adding the number 10 with the string 'dog', but there is ntohing for 'false' to be compared to.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

- On any page that we develope, condition statements can be used to determine when and when not to run certain codes.

6. Give an example of when a Loop is useful in JavaScript.

- If there is specific code that you want to run repeatedly or even with different variables on your page, a loop would be the best option to use.

> ## Things I want to know more about
