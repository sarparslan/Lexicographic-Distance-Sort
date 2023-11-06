# Lexicographic-Distance-Sort 

This Java program implements a custom String sorting algorithm that sorts two arrays of Strings of the same length. The sorting is based on specific rules as described below:

## Sorting Rules

1. **Distance Calculation:**
   - Each letter is assigned a number starting from 1 for "A" and increasing incrementally to 26 for "Z".
   - The integer value of a String is determined by summing the letter numbers. For example, the integer value of "abj" is 1210.
   - Calculate the distance between two Strings at the same indexes by subtracting their integer values. For example, the distance between "abj" and "bal" at index "0" is |1210 - 2112| = 902.

2. **Even Distance:**
   - If the distance value is even, sort the String from the first array based on the order of the corresponding String from the second array.
   - Sort the String in the first array according to the character order in the corresponding String from the second array.
   - Add any characters in the first String that are not present in the second String to the end of the sorted String.

3. **Odd Distance:**
   - If the distance value is odd, sort the String lexicographically in ascending order.

## Usage

1. Clone this repository to your local machine.

2. Compile and run the Java program using your preferred Java development environment.

3. Follow the prompts to input the necessary parameters and perform custom String sorting based on the specified rules.

## Input Format

- Provide two arrays of Strings, each of the same length.
- Ensure that the Strings in the second array do not contain duplicate characters.

## Output Format

- The program will display the sorted Strings based on the specified rules.

<img width="505" alt="Screenshot 2023-11-06 at 23 00 03" src="https://github.com/sarparslan/Lexicographic-Distance-Sort/assets/96438389/5d271947-bb63-41e2-a970-74a5b1d76e30">
