# Pointers
## Aim:
To study and implement the concept of pointers in C++ and perform operations such as pointer increment, array reversal, and arithmetic calculations.

## Theory:
A pointer in C++ is a variable that stores the memory address of another variable.

Declaration: int *ptr;

Initialization: ptr = &variable;

Dereferencing: *ptr gives the value stored at the address.

Key facts:

Pointer arithmetic changes the memory address based on the data type size.

Incrementing a pointer (ptr++) moves to the next element in memory for that type.

Pointers can be used to access and modify arrays, pass large data structures to functions efficiently, and implement dynamic memory allocation.

## Algorithms:

### 1. Pointer Increment

Start.

Declare an array of a certain data type (e.g., int arr[]).

Declare a pointer and assign it the base address of the array.

Display the address and value pointed by the pointer.

Increment the pointer (ptr++).

Display the new address and value.

Repeat as needed.

Stop.

### 2. Array Reversal
Start.

Declare an array and take its elements as input.

Set two indices: start = 0, end = size - 1.

While start < end:

Swap arr[start] with arr[end].

Increment start, decrement end.

Display the reversed array.

Stop.

### 3. Arithmetic Operations
Start.

Input two numbers.

Display a menu for:

Addition

Subtraction

Multiplication

Division

Take user choice.

Perform the selected operation using operators or functions.

Display the result.

Stop.

## Conclusion:
Pointers in C++ allow direct memory manipulation, enabling efficient array processing, dynamic memory allocation, and flexible function parameter passing. Pointer increment, array reversal, and arithmetic operations demonstrate the practical applications of pointers in real programming.
