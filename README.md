#include <stdio.h>

int main() {
    int num; // Variable to store the user input number

	    //Okonta Destiny
       //CMP2307643
      //D1010520
     //Software Engineering 
    // Prompt the user to enter a number 
    printf("Enter an integer: ");
    scanf("%d", &num); // Read the integer input from the use

    // Check if the number is even or odd
    if (num % 2 == 0) {
        printf("%d is even number.\n", num);
    } else {
        printf("%d is odd number.\n", num);
    }
   // Return 0 to indicate successful program execution
    return 0;
}
