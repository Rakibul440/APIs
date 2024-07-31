# JSON

JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy to read and write. Here's an overview of JSON with code examples:

## JSON Syntax

- JSON data is represented as a collection of key-value pairs
- Keys are strings, and values can be strings, numbers, booleans, arrays, or objects
- JSON data is surrounded by curly braces {} or square brackets []

## JSON Data Types

- Strings: "hello world"
- Numbers: 123
- Booleans: true or false
- Arrays: ["apple", "banana", "orange"]
- Objects: {"name": "John", "age": 30}

## JSON Example

```
{
  "name": "John",
  "age": 30,
  " occupation": "Developer",
  "address": {
    "street": "123 Main St",
    "city": "New York",
    "state": "NY"
  },
  "interests": ["reading", "hiking", "coding"]
}

```

## Parsing JSON

- In JavaScript, you can parse JSON data using `JSON.parse()`
- In other languages, you can use libraries like json in Python or Jackson in Java

Example (JavaScript):

```
const jsonData = '{"name": "John", "age": 30}';
const data = JSON.parse(jsonData);
console.log(data.name); // Output: John

```

## Generating JSON

- In JavaScript, you can generate JSON data using `JSON.stringify()`
- In other languages, you can use libraries like json in Python or Jackson in Java

Example (JavaScript):

```
const data = { name: "John", age: 30 };
const jsonData = JSON.stringify(data);
console.log(jsonData); // Output: {"name": "John", "age": 30}

```

## JSON in APIs

- JSON is commonly used as a data format in web APIs
- APIs typically return JSON data in response to requests

Example (API Response):

```
{
  "status": "success",
  "data": {
    "name": "John",
    "age": 30
  }
}

```
