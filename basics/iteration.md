# Iteration

Iteration is the process of repeatedly calling a set of code. Through the use of loops, we can execute the code that the user wants to repeat.

## For Loop
Structure that allows us to run a set of code a certain number of times.

Example:
```cpp
for(int i = 0; i < 10; i++){
    //body
}

// This loop will run 10 times
```


## While Loops
Structure that runs until the conditional statement is false.

Example:
```cpp
int i = 0;

while(i < 10){
    //body

    i++;
}

// This will run 10 times
```

## Do-While Loop
Structure that first runs the body of the loop, then checks to see if the conditional is false. If the conditional is true, the code will run again.

Example:
```cpp
int i = 0;
do{
    //body

    i++;

}while(i < 10);
```

