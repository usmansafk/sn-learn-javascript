# Welcome to Learn JavaScript on the Now Platform!

*JavaScript*
Lesson #:
- 1 - Getting Started
- 2 - Statements and Syntax
- 3 - Variables
- 4 - Mathematical operators
- 5 - Common error messages
- 6 - Strings
- 7 - Special characters
- 8 - Changing and detecting variable types
- 9 - Commenting
- 10 - Arithmetic Operators
- 11 - If statements | Boolean logic
- 12 - The ternary operator
- 13 - if/else | switch
- 14 - Truthy and Falsy
- 15 - while loop
- 16 - for loop
- 17 - do-while
- 18 - Nested loops
- 19 - functions
- 20 - try / catch/ finally

*Advanced / SNOW Topics:*

Lesson #:
- 21 -
Simple Database query |
Get and display numbers on all incidents v2 |
dot notation vs .getValue('') |
getting a single record quickly - Just need one record? Use .get(SYSID) or .get('fieldName', fieldValue)

- 22 - Arrays | Loops and Arrays

- 23 -
forEach with external function |
embedded forEach |
.forEach(function (item, index, arr)

- 24 - Array Methods/ Functions
join(',') |
.push('Dave');
list.pop();
.shift();
.unshift('Jason', 'Andrew');
splice(position, n-remove, value1, value2, ..., valueX) - add/remove elements somewhere in the middle, .splice(2, 0, "Cary", "Henri");
slice(start, end) - extract part of an array in to another array
.reverse(); - Reverse the elements of an array
.addQuery('priority', '1'); - Getting the value
.query();

- 25 - SNows: ArrayUtil
.unique(list);

- 26 - Objects
dot notation |
bracket notation |
Shortcut objects |

- 27 - Objects hasOwnProperty("<>");

- 28 - Get object keys / values

- 29 - Array of Objects
.length;
for loop - looping through array of objects

- 30 - Stringify | Parse

- 31 - Advanced Strings
.indexOf('Email'); - Find the position of a character or substring |
Use the position of a character/substring as a condition - i.e. see if string exists. If null, prints -1:
if (description.indexOf('error') >= 0) {
gs.info("exists);
} |
.substring(pos, pos + 11); |
toUpper or toLower for better matching

- 32 - Recursion

- 33 - Classes, Objects, and Prototypes |
Initialize values

- 34 - Passing objects to functions

- 35 - Inheritance

- 36 - REST API
(GET) resource |
Scripted REST API with query parameters |
Scripted REST API with path parameters |
Scripted REST API (POST) with request body payload |
Scripted REST API with POST and response

//------------------------------------------------------------------------------

This repository contains examples used in the video series in folders corresponding to the lessons.
You can find the video series on the ServiceNow Developer
[YouTube channel](https://www.youtube.com/watch?v=62Nabpb94Jw&list=PL3rNcyAiDYK2_87aRvXEmAyD8M9DARVGK&index=1)

Scripts use the naming structure **L(lesson#)S(script#).js**.
Example, L09S01.js refers to Lesson 9, script example 1.
Solutions to lab exercises can also be found in the _Lab Solutions_ folder.

# Helpful resources mentioned in this series

- [Codecademy.com (JavaScript)](https://www.codecademy.com/catalog/language/javascript)
- [W3Schools.com (Javascript)](https://www.w3schools.com/js/default.asp)
- [ServiceNow Developer Program](https://developer.servicenow.com)
- [Scripting in ServiceNow Fundamentals](https://www.servicenow.com/services/training-and-certification/scripting-in-servicenow-training.html)
- [ServiceNow Docs](https://docs.servicenow.com)
- [ServiceNow Technical Best Practices](https://developer.servicenow.com/dev.do#!/guides/quebec/now-platform/tpb-guide/scripting_technical_best_practices)
- [TechNow webinars](https://devlink.sn/technow)
- [ServiceNow Community](https://community.servicenow.com)
- [Stephen Bell's Scripting Best Practices Videos](https://www.youtube.com/user/ServiceNowCommunity/search?query=scripting+best+practices)
