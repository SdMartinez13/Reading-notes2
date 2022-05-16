Readings: Problem Domain, Objects, and the DOM
===

***Understanding the problem domain is the hardest part of programming***

-[Link to Reading](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)

- Figure out what the major components of the picture are

- Sort the pieces by color or component

- Put together all the border pieces

- Put together each component of the picture from the piles you created

***What's the difference between primitive values and object references in JS?***

-[Link to Reading](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

- JavaScript currently supports eight data types. All of these data types (Booleans, Null, Undefined, Number, BigInt, String, Symbol) are primitive values except for object references.

- Many common data types such as arrays, functions, and dates are object references under the hood.

- Primitive values can be stored in variables directly. Objects, on the other hand, are stored as references. A variable that has been assigned an object does not store that object directly, it stores the memory address of the location that the object exists at.

- Primitive values are immutable — they cannot be changed after being created. Object references, however, are mutable and can be changed.

***Duckett JS Book***
---

**Chapter 3 "object Literals"(pp.100-105)**

- an object is a series of variables and functions that represent something from the world around you

- in an object, variables are known as properties of the object

- functions are known as methods of the object

- web browsers implement objects that represent both the web browser window and the document loaded into the browser window.

**Chapter 5 "Document Object Model"(pp.183-242)**

- The browser represents the page using a DOM tree.

- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.

- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one node, it will always return a NodeList.
- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree.

## Things I want to know more about

***There was a lot of reading on Document object model which I really need to read again and understand it.