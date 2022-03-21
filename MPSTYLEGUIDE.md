# Mind Professionals Style Guide
This markdown document includes the style guide for the Mind Professionals codebases

## Rules
* Use 4 spaces for indentation
* Use double quotes for strings
* Use single quotes for characters
* No unused variables
* Add a space after keywords
* Don't have a space before named function parenthesis
* Add a space before anonymous function parenthesis
* Always use `===` instead of `==`
* Infix operators must be spaced
* Commas should have a space after them
* Keep else statements on the same line as their curly braces
* Always use curly braces for if statements
* Always handle the `err` function parameter
* Multiple blank lines are not allowed, only 1
* For the ternary operator, place `?` and `:` on their own lines
* For variable declarations, each declaration will be written in their own statement
* Wrap conditional assignments with additional parenthesis to make clear that the expression is intentionally an assignment
* Add spaces inside single line blocks
* Use camelcase when naming variables and functions
* Trailling commas are not allowed
* Commas must be placed at the end of the current line
* Dot should be on the same line as property
* No space between function identifiers and their invocations
* Add space between colon and value only, in key value pairs
* Constructor names must begin with a capital letter
* Constructors with no arguments must still be invoked with parenthesis
* Constructors of derived classes must call `super()`
* Use array literals instead of array constructors where possible
* Avoid using `arguments.callee` and `arguments.caller`
* Avoid modifying variables of class declarations
* Avoid modifying variables declared using const
* Avoid constant expressions in conditions (except loops)
* No control characters in regular expressions
* No `debugger` statements
* No `delete` operator on variables
* No duplicate arguments in function definitions
* No duplicate name in class members
* No duplicate keys in object literals
* No duplicate `case` labels in `switch` statements
* Use a single import statement per module
* No emepty character classes inr egular expressions
* No empty destructuring patterns
* No using `eval`
* No extending native objects
* Avoid unncessary function binding
* Avoid unnecessary boolean casts
* Use `break` to prevent fallthrough in `switch` cases
* No floating decimals
* No function reassignment
* No reassingning global variables
* No implied `eval`
* No invalid regular expression strings in `RegExp` constructors
* No irregular whitespace
* No using `__iterator__`
* No labels that share a name with an in scope variable
* No label statements
* No lone blocks
* No mixed spaces and tabs
* No multiple spaces except for indentation
* No multiline strings
* No `new` without assigning object to a variable
* No using the `Function` constructor
* No using the `Object` constructor
* No using `new require`
* No using the `Symbol`
* No using primitivae wrapper instances
* No calling global object properties as functions
* No octal literals
* No octal escape sequences
* Avoid string concatenation when using `__dirname` and `__filename`
* Avoid using `__proto__`
* No redeclaring variables
* Avoid multiple spaces in regular expression literals
* Assignments in return statements must be surrounded by parenthesis
* Avoid assigning a variable to itself
* Avoid comparing a variable to itself
* Avoid using the comma operator
* Restricted names should not be shadowed
* Tabs should not be used
* Regular strings must not contain templat literal placeholders
* `super()` must be called before using `this`
* Only `throw` an `Error` object
* Whitespace not allowed at end of line
* Initializing to `undefined` is not allowed
* No unmodified conditions of loops
* No ternary operators when simpler alternatives exist
* No unreachable code after `return`, `throw`, `continue`, and `break` statements
* No flow control statements in `finally` blocks
* The left operand of relational operators must not be negated
* Avoid unnecessary use of `.call()` and `.apply()`
* Avoid using unnecessary computed property keys on objects
* No unnecessary constructor
* no unnecessary use of escape
* No whitespace before properties
* No using `with` statements
* Maintain consistency of new lines between object properties
* No padding within blocks
* No whitespace between spread operators and their epressions
* Semicolons must have a space and no space before
* Must have a space before blocks
* No spaces inside parentheses
* Unary operators must have a space after
* Use spaces inside comments
* No spacing in template strings
* Use `isNaN()` when checking for `NaN`
* `typeof` must be compared to a valid string
* Immediately Invoked Function Expressions (IIFEs) must be wrapped
* The `*` in `yield*` expressions must have a space before and after
* Avoid Yoda conditions
## Semicolons
* Always use semicolons
* Never start a line with `(`, `[`, `+`, `*`, `/`, `-`, `,`, `.`
