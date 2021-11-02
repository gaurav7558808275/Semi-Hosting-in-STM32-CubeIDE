# Semi-Hosting-in-STM32-CubeIDE

1) ## Step 1
We have to add two function that will be used as a printf statements
```
// function prototype
extern void initialise_monitor_handles();

//call these functions insider the main
  initialise_monitor_handles();
  printf("application is running \n"); // sample send data. always end with '\n'


