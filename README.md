Ohm's Law Calculator

Project Description
This project is a simple C++ calculator that uses Ohm's Law to calculate electrical current from voltage and resistance.

The formula used is:

I = V / R

Where:
- I = Current (amperes)
- V = Voltage (volts)
- R = Resistance (ohms)

Input Format
The program accepts two numbers separated by a space:
1. Voltage
2. Resistance

Example input:
`12 4`

Expected Output
For the input `12 4`, the program displays:

`Current: 3 A`

If the resistance is zero or negative, or the input is not numeric, the program displays:

`Invalid input`

How to Compile and Run
Compile the program using:

`g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o app`

Run the program:

`./app`

Enter the voltage and resistance when prompted.
Running Tests
Run the acceptance tests using:

`bash test.sh`

If both tests pass, the terminal displays:

`All acceptance tests passed`

Limitations
- The program only calculates current using Ohm's Law.
- Resistance must be greater than zero.
- The program does not include a graphical interface.
- The program expects numeric input.

Debugging Reflection
During this project, I learned how to compile and test a C++ program using the terminal. I also practiced fixing errors in the code and test files so the acceptance tests would pass.
