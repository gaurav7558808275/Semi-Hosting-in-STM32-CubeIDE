# Semi-Hosting-in-STM32-CubeIDE

## Step 1
We have to add two function that will be used as a printf statements
```
// function prototype
extern void initialise_monitor_handles();

//call these functions insider the main
  initialise_monitor_handles();
  printf("application is running \n"); // sample send data. always end with '\n'
```
## Step 2
Add these in the command section that is found in the debug console
**Route**
right cick -> go to debug -> debug configuration -> add these commands
```
monitor arm semihosting enable 
```
## Step 3

Use the printf() command to print the required data through semi Hosting.

