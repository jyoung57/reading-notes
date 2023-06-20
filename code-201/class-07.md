# Read: Class-07

## Domain Modeling

1. Explain why we need domain modeling.

* A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## HTML Table Basics

1. Why should tables not be used for page layouts?

* Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.

* Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

* Tables are not automatically responsive: When you use proper layout containers (such as <header>, <section>, <article>, or <div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

2. List and describe 3 different semantic HTML elements used in an HTML <table>.

* <table> - This is used as the body for your table within HTML.

* <td> - This is used for inputing table data.

* <tr> - This is used for inputting table rows witin tables. 

## Intro to Constructors

1. What is a constructor and what are some advantages to using it?

* Constructors are almost similar to methods except for two things - its name is the same as the class name and it has no return type. Sometimes constructors are also referred to as special methods to initialize an object.  A constructor will allow you to do multiple object literals in one. 

2. How does the term this differ when used in an object literal versus when used in a constructor?

* It doesnt.

## Object Prototypes Using a Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question.

* 

## Things I want to know more about.