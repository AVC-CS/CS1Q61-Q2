<!-- [A6-2] (https://prezi.com/p/edit/-xdwv8fik5xk/) -->

<!--
## ![A6-2](https://nimbus-screenshots.s3.amazonaws.com/s/4f4a634adf0c7c85fc178d5c682b7302.png) -->

## Open the "q2.cpp"

> Complete the following functions to do the following works:

The program generates three random numbers and then find the min number among these values. We need to develop three functions as follows:

1. get three random numbers

void gerRandnum(int &n1, int &n2, int &n3);  
// In this function, generate three random numbers and assign the values to the parameter n1, n2, and n3

2. find the minimum number and return to the main function.

int  findMin(int n1, int n2, int n3);  
// The return value : the min among n1, n2 and n3.

3. Print the results

void printResult(int n1, int n2, int n3, int min);  
// Print out the results with the original numbers and the minimum value

4. Make the main function to drive all these functions.

// In main( ), call the functions  
getRandnum(n1, n2, n3);  
min = findMin(n1, n2, n3);  
printResult(n1, n2, n3, min);
