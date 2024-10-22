# Diamond Pattern Printer

## Overview

This Java program prints a diamond shape pattern made of asterisks (`*`). The diamond has a specified height, which is set by the variable `n`. The program prints the top half of the diamond followed by the bottom half, resulting in a symmetrical diamond shape.

## How It Works

- The variable `n` represents the **half-height** of the diamond. It controls how many rows the top half of the diamond has. The total height of the diamond is `(2 * n - 1)` rows.
- The program consists of two parts:
  1. **Top Half**: The `for` loop iterates to print increasing rows of asterisks, with leading spaces to align them correctly to form a triangle.
  2. **Bottom Half**: Another `for` loop iterates to print decreasing rows of asterisks, also with leading spaces, to complete the diamond shape.

### Details
- **Top Half**: For each row, the program first prints a number of spaces to ensure proper alignment, then prints `2 * i + 1` asterisks (`*`). This creates a progressively larger pattern that resembles the top half of a diamond.
- **Bottom Half**: Similar to the top half, the bottom half decreases the number of asterisks row by row until a single asterisk is printed.

## Example Output

When `n` is set to `5`, the output will be:

```
    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *
```

## How to Run the Program

1. Make sure you have Java installed on your system.
2. Copy the Java code into a file named `Main.java`.
3. Compile the Java file using the following command:

   ```
   javac Main.java
   ```

4. Run the program with the following command:

   ```
   java Main
   ```

5. The program will print a diamond pattern of height `n`.

## Author

This program was created by **hekimcanaktas**.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software. See the [LICENSE](LICENSE) file for more details.

