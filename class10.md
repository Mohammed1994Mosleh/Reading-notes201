# Reading class10:
## Erorr handling and debugging:

- ORDER OF EXECUTION:
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex.

![](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)

### The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

#### EXECUTION CONTEXT:
- GLOBAL CONTEXT
- FUNCTION CONTEXT
- EVAL CONTEXT (NOT SHOWN)

#### EXECUTION CONTEXT & HOISTING:
Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE
2. Exceutive.

#### ERROR OBJECTS:
- Syntax Error:
SYNTAX IS NOT CORRECT
- Ref erenceError:
VARIABLE DOES NOT EXIST
- Eval Error:
INCORRECT USE OF eval() FUNCTION
- URI Error:
INCORRECT USE OF URI FUNCTIONS
- Type Error:
VALUE IS UNEXPECTED DATA TYPE
- Range Error:
NUMBER OUTSIDE OF RANGE
- Error:
GENERIC ERROR OBJECT
- NaN:
NOT AN ERROR

![catch error](https://javascript.info/article/try-catch/try-catch-flow.svg)