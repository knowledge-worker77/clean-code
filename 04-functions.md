## One argument at a time

The ideal way to create functions is that they shouldn't have any arguments in them but in most cases you'll have to pass one or two arguments in your functions.

If you're passing three or more arguments in your functions without a proper reason then that could be the cause of many problems when the code base grows bigger. This also makes testing more harder for you.

## Side effects of functions

Your functions **WILL** have side effects although your functions only do one thing but they also do many hidden things like changing the values of variables or passing them as globals.

Some functions can also have output arguments, arguments in functions are used for input but they sometimes can also be used for outputs as well. This was common before modern OOP languages were created and is now not needed.

## Separating commands and queries

Your function should change the state of an object, or it should return some information about that object and not do both.  A simple example of this could be that if you want to take an input of a user's name and then display it then your code should have exactly two functions in it.

Returning error codes from command functions is a subtle violation of command query separation. It promotes commands being used as expressions in the predicates of if statements. If you use exceptions instead of returned error codes, then the error processing code can be separated from the code and can be simplified

## Error handling with functions

Try/catch blocks are ugly in their own right. They confuse the structure of the code and mix error processing with normal processing. So it is better to extract the bodies of the try and catch blocks out into functions of their own.

Again stating that each function should do one thing. Error handing is one thing. Thus, a function that handles errors should do nothing else. This implies that if the keyword try exists in a function, it should be the very first word in the function and that there should be nothing after the catch/finally blocks.

## Keeping functions DRY

Duplication is a problem because it bloats the code and will require modification should the algorithm ever have to change. It is also a opportunity for an error of omission. Duplication may be the root of all evil in software. Many principles and practices have been created for the purpose of controlling or eliminating it.

#web-development #Books 