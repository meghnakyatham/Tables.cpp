# Tables.cpp


# Multiplication Table Generator

This program generates the multiplication table for a given number 'n'. It takes an integer input 'n' from the user and then displays the multiplication table of 'n' from 1 to 10.

## How to Use

1. Compile the Program:
   Open a terminal or command prompt and navigate to the directory containing the `main.cpp` file. Use a C++ compiler (e.g., g++) to compile the program.
   
   ```bash
   g++ main.cpp -o multiplication_table
   ```

2. Run the Program:
   After successfully compiling the program, you can run the executable.

   ```bash
   ./multiplication_table
   ```

3. Input:
   The program will prompt you to enter an integer value for 'n'. Enter the desired number and press Enter.

4. Output:
   The program will display the multiplication table of 'n' from 1 to 10. Each line will show the equation `n x i = result`, where 'i' varies from 1 to 10.

5. Exit:
   After displaying the multiplication table, the program will terminate.

## Example

```
Enter n: 7
7x1=7
7x2=14
7x3=21
7x4=28
7x5=35
7x6=42
7x7=49
7x8=56
7x9=63
7x10=70
```

## Note

This program uses the `iostream` library for input and output operations. The `using namespace std;` statement allows us to use the `cut` and `cin` objects without specifying the `std::` namespace prefix.

Feel free to experiment with different values of 'n' to generate multiplication tables for various numbers.

