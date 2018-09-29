# scripts
Writing scripts in NodeJS

Homework:

- [ ] Write a script called `greet.js` that will accept one argument: any string. `greet.js` should print `Hello ____` with `____` being the given string. Entering `node greet.js Kramer` into the command line should print out `Hello Kramer`. `greet.js` will also export a function that provides this functionality by accepting the argument into the function.
- [ ] Write a script called `calc.js` that will accept three arguments in this order: 1) A string that should be add, subtract, multiply, or divide, 2) the first number, and 3) the second number. The script should print the result of the calculation. Entering `node calc.js divide 24 4` should print out `6`. `calc.js` will also export a function that provides this functionality by accepting the arguments into the function.
- [ ] Write a script called `greetAndCalc.js` that imports `greet.js` and `calc.js`, and will accept four arguments in this order: 1) any string, 2) a string that should be add, subtract, multiply, or divide, 2) the first number, and 3) the second number. The script should greet the first given string and then print the result of the calculation. Entering `node greetAndCalc.js Kramer divide 24 4` should print out `Hello Kramer 6`. Again,`greetAndCalc.js` should provide this functionality by importing `greet.js` and `calc.js`. When running `greetAndCalc.js`, `greet.js` and `calc.js` should not print anything out.
- [ ] BONUS: Write a script called `index.js` that will print out the names of all OTHER files in the same directory, WITHOUT hard-coding the filenames. So in this case, it should print out `calc.js greet.js greetAndCalc.js`. And if you were to add a file called `hello.js`, running index.js WITHOUT changing the code will print out `calc.js hello.js greet.js greetAndCalc.js`.