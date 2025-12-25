# C-project
Calculator Program in C

A simple console-based calculator written in C that supports multiple operations, including addition, subtraction, multiplication, division, modulus, square, square root, power, and factorial.

📌 Features

Perform basic arithmetic operations:

Addition

Subtraction

Multiplication

Division

Modulus

Advanced operations:

Square

Square root (handles negative inputs with a message)

Power

Factorial (handles negative inputs with a message)

Interactive menu-driven console interface

Input validation for division by zero and negative inputs, where applicable

Continuous operation untilthe  user chooses to exit

🛠️ Technologies Used

C Programming Language

Standard C libraries (stdio.h, stdlib.h, math.h)

📥 How to Compile and Run

Save the code to a file, for example, calculator.c.

Open a terminal or command prompt.

Compile the program with GCC:

gcc calculator.c -o calculator -lm


Note: The -lm flag links the math library.

Run the executable:

./calculator


(On Windows, run calculator.exe)

📋 Usage

After running the program, you will see a menu with options to select an operation.

Enter the corresponding number (1 to 9) to perform that operation.

For each operation, follow the prompts to input numbers.

Enter 0 to exit the program.

🧠 How It Works

The program displays a menu and waits for user input.

Based on user's choice, it calls the respective function to perform the calculation.

Each function reads user input, performs the calculation, and prints the result.

Special checks are included for:

Division/modulus by zero (prints error message)

Negative input for square root and factorial (prints a message that the result can’t be defined or is complex)

⚠️ Error Handling

Division or modulus by zero is prevented with an error message.

The square root of negative numbers is not calculated, but is noted as complex.

Factorial of negative numbers is invalid and is notified.

Invalid menu selections show an “Operator error!” message.

📝 License

This program is free to use, modify, and distribute for educational and personal purposes.
