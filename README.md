What is scope? Your explanation should include the idea of global vs. block scope.
Scope is declaration of variable.

Global:
let myVariable = "example";
myFuction(){
  console.log(myVariable);
}

Block:
myFuction(){
  let myVariable = "example";
  console.log(myVariable);
}

Why are global variables avoided?
Because it can be accessed and chanced in another function or file.

Explain JavaScript's strict mode.
Strict mode is when we force to use let or cont to declare variables.

What are side effects, and what is a pure function?
Side effects is when a function uses a globar variable, and a pure function is when doesn't.
