# Conditionals

A way of handling decisions by checking to see if a certain criteria is met.

## If Statement
Runs a block of code if the condition is true.

Example:
```cpp
if (condition){
    // This will run if the condition is true
}
```

## If-Else Statement
Checks if initial condition is true. If not, the code block in the else statement will run.

Example:
```cpp
if (condition){
    // This will run if the condition is true
} 
else{
    // This will only run if the condition above is false    
}
```

## If-Else-If Statement
Like the previous statement, but now the else will also have a conditional statement.

Example:
```cpp
if (condition){
    // Runs if the initial condition is true
}
else if(condition){
    // Runs if the condition above is false and this condition is true.
}
else{
    // Runs if the previous conditionals are false
}
```

## Switch Statement
Statement that jumps to a case based on the value of the expression. **The expression
must evaluate to an integer or a character.**

- If the expression does not match any cases, the default statement will run

Example with an Integer:
```cpp
int value = 2;

switch (value){
    case 1:
        // this will not run
        break;
    case 2:
        // this will run
        break;
    case 3:
        // this will not run
        break;
    default:
        // this will not run
        break;
}
```

Example with a Character:
```cpp
char value = a;

switch (value){
    case a:
        // this will run
        break;
    case b:
        // this will not run
        break;
    case c:
        // this will not run
        break;
    default:
        // this will not run
        break;
}
```

Example Where No Cases Match the Expression:
```cpp
char value = d;

switch (value){
    case a:
        // this will not run
        break;
    case b:
        // this will not run
        break;
    case c:
        // this will not run
        break;
    default:
        // this will run
        break;
}
```
