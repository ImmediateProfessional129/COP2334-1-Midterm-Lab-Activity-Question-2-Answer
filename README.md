# COP2334-1-Midterm-Lab-Activity-Question-2-Answer
This is a repository for the Midterm Lab Activity Question 2 Answer

// This program is desinged to establish the amount of numbers that are even or odd, and if they are divisible by 2.

// Include the iostream library
#include <iostream>
using namespace std; // Using standard namespace
int CountEvens(int count1, int count2, int count3, int count4, int count5) { // Function to count the amount of even numbers
  int CountEven = 0; // Initialize the count of even numbers to 0.
  if (count1 % 2 == 0) CountEven++; // Check if the first number is even and increment the count if it is.
  if (count2 % 2 == 0) CountEven++; // Check if the second number is even and increment the count if it is.
  if (count3 % 2 == 0) CountEven++; // Check if the third number is even and increment the count if it is.
  if (count4 % 2 == 0) CountEven++; // Check if the fourth number is even and increment the count if it is.
  if (count5 % 2 == 0) CountEven++; // Check if the fifth number is even and increment the count if it is.
  return CountEven; // Return the count of even numbers.
}

// Function to count the amount of odd numbers
int CountOdds(int count1, int count2, int count3, int count4, int count5) {
  int CountOdd = 0; // Initialize the count of odd numbers to 0.
  if (count1 % 2 != 0) CountOdd++; // Check if the first number is odd and increment the count if it is.
  if (count2 % 2 != 0) CountOdd++; // Check if the second number is odd and increment the count if it is.
  if (count3 % 2 != 0) CountOdd++; // Check if the third number is odd and increment the count if it is.
  if (count4 % 2 != 0) CountOdd++; // Check if the fourth number is odd and increment the count if it is.
  if (count5 % 2 != 0) CountOdd++; // Check if the fifth number is odd and increment the count if it is.
  return CountOdd; // Return the count of odd numbers.
}

int main() { // Main function
  int count1 = 3; // Initialize the first number to 3.
  int count2 = 8; // Initialize the second number to 8.
  int count3 = 14; // Initialize the third number to 14.
  int count4 = 23; // Initialize the fourth number to 23.
  int count5 = 35; // Initialize the fifth number to 35.
  cout << "Number of evens: " << CountEvens(count1, count2, count3, count4, count5) << endl; // Print the count of even numbers.
  cout << "Number of odds: " << CountOdds(count1, count2, count3, count4, count5) << endl; // Print the count of odd numbers.
  return 0; // Return 0 to indicate a successful program execution.
}
