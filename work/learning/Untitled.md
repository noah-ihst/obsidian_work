# Literal (computer programming)

From Wikipedia, the free encyclopedia

[Jump to navigation](https://en.wikipedia.org/wiki/Literal_(computer_programming)#mw-head) [Jump to search](https://en.wikipedia.org/wiki/Literal_(computer_programming)#searchInput)

Notation for representing a fixed value in source code

In [computer science](https://en.wikipedia.org/wiki/Computer_science "Computer science"), a **literal** is a notation for representing a fixed [value](https://en.wikipedia.org/wiki/Value_(computer_science) "Value (computer science)") in [source code](https://en.wikipedia.org/wiki/Source_code "Source code").[\[1\]](https://en.wikipedia.org/wiki/Literal_(computer_programming)#cite_note-1)[\[2\]](https://en.wikipedia.org/wiki/Literal_(computer_programming)#cite_note-2) Almost all programming languages have notations for atomic values such as [integers](https://en.wikipedia.org/wiki/Integer_(computer_science) "Integer (computer science)"), [floating-point numbers](https://en.wikipedia.org/wiki/Floating-point_number "Floating-point number"), and [strings](https://en.wikipedia.org/wiki/String_(computer_science) "String (computer science)"), and usually for [booleans](https://en.wikipedia.org/wiki/Boolean_datatype "Boolean datatype") and [characters](https://en.wikipedia.org/wiki/Character_(computing) "Character (computing)"); some also have notations for [elements of enumerated types](https://en.wikipedia.org/wiki/Enumerated_type "Enumerated type") and compound values such as [arrays](https://en.wikipedia.org/wiki/Array_data_structure "Array data structure"), [records](https://en.wikipedia.org/wiki/Record_(computer_science) "Record (computer science)"), and [objects](https://en.wikipedia.org/wiki/Object_(computer_science) "Object (computer science)"). An [anonymous function](https://en.wikipedia.org/wiki/Anonymous_function "Anonymous function") is a literal for the [function type](https://en.wikipedia.org/wiki/Function_type "Function type").

In contrast to literals, [variables](https://en.wikipedia.org/wiki/Variable_(programming) "Variable (programming)") or [constants](https://en.wikipedia.org/wiki/Constant_(computer_science) "Constant (computer science)") are symbols that can take on one of a class of fixed values, the constant being constrained not to change. Literals are often used to initialize variables, for example, in the following, 1 is an integer literal and the three letter string in "cat" is a string literal:

int a \= 1;
string s \= "cat";

In [lexical analysis](https://en.wikipedia.org/wiki/Lexical_analysis "Lexical analysis"), literals of a given type are generally a token type, with a grammar rule, like "a [string of digits](https://en.wikipedia.org/wiki/String_of_digits "String of digits")" for an integer literal. Some literals are specific [keywords](https://en.wikipedia.org/wiki/Keyword_(programming) "Keyword (programming)"), like `true` for the boolean literal "true".

In some [object](https://en.wikipedia.org/wiki/Object_(computer_science) "Object (computer science)")\-oriented languages (like [ECMAScript](https://en.wikipedia.org/wiki/ECMAScript "ECMAScript")), objects can also be represented by literals. Methods of this object can be specified in the object literal using [function literals](https://en.wikipedia.org/wiki/Function_literals "Function literals"). The brace notation below, which is also used for array literals, is typical for object literals:

{"cat", "dog"}
{name: "cat", length: 57}

## Literals of objects

In [ECMAScript](https://en.wikipedia.org/wiki/ECMAScript "ECMAScript") (as well as its implementations [JavaScript](https://en.wikipedia.org/wiki/JavaScript "JavaScript") or [ActionScript](https://en.wikipedia.org/wiki/ActionScript "ActionScript")), an object with methods can be written using the object literal like this:

'var newobj \= {
  var1: true,
  var2: "very interesting",
  method1: function () {
    alert(this.var1)
  },
  method2: function () {
    alert(this.var2)
  }
};
newobj.method1();
newobj.method2();
'
These object literals are similar to [anonymous classes](https://en.wikipedia.org/wiki/Anonymous_class "Anonymous class") in other languages like [Java](https://en.wikipedia.org/wiki/Java_(programming_language) "Java (programming language)").

The [JSON](https://en.wikipedia.org/wiki/JSON "JSON") data interchange format is based on a subset of the JavaScript object literal syntax, with some additional restrictions (among them requiring all keys to be quoted, and disallowing functions and everything else except data literals). Because of this, _almost_ every valid JSON document (except for some subtleties with escaping) is also valid JavaScript code, a fact exploited in the [JSONP](https://en.wikipedia.org/wiki/JSONP "JSONP") technique.