# 42dico

Function names used in C programming course Piscine ordered by 42Lausanne exercices. * Does not include RushXX, ExamXX, ShellXX.


# C 00

1. **putchar**: This function takes a single character as an argument and prints it to the standard output. It's similar to the standard C function `putchar()`.

2. **print_alphabet**: This function prints the English alphabet ('a' to 'z' or 'A' to 'Z') to the standard output.

3. **print_reverse_alphabet**: This function prints the English alphabet in reverse order ('z' to 'a' or 'Z' to 'A') to the standard output.

4. **print_numbers**: This function prints the digits (0 to 9) to the standard output.

5. **is_negative**: This function takes an integer as an argument and checks if it's negative. It could return a boolean value or print a result to the standard output.

6. **print_comb**: This function prints all possible combinations of some set of numbers or characters. The specific set it operates on might be defined within the function or passed as an argument.

7. **print_comb2**: This function is a variation of `print_comb`. It might print combinations in a different order or format, or operate on a different set of numbers or characters.

8. **putnbr**: This function takes an integer as an argument and prints it to the standard output. It's a common task in C programming.

9. **print_combn**: This function is another variation of `print_comb`. It might take an integer 'n' as an argument and print all combinations of 'n' elements from a specific set. 

# C 01

1. **ft**: This function accepts a pointer to an integer as a parameter and sets the value pointed by the integer pointer to 42. The function doesn't return anything (void).

2. **ultimate_ft**: This function takes a nine-level deep pointer to an integer as an argument and sets the value pointed by this nine-level pointer to 42. The function doesn't return anything (void).

3. **swap**: This function swaps the values of two variables. It would likely take two pointers to variables as arguments and interchange the values at those memory addresses.

4. **div_mod**: This function performs both division and modulo operations. It might take two integer arguments and two pointers to store the results of the division (quotient) and modulo (remainder).

5. **ultimate_div_mod**: This function might be a more advanced or comprehensive version of "div_mod", maybe handling more edge cases or additional functionality.

6. **putstr**: This function takes a string as an argument and prints it to the standard output. It's similar to the standard C function `puts()`.

7. **strlen**: This function calculates and returns the length of a string. It's similar to the standard C function `strlen()`.

8. **rev_int_tab**: This function reverses the order of elements in an integer array.

9. **sort_int_tab**: This function sorts an integer array in ascending or descending order.

# C 02

1. **strcpy**: A standard function that copies the string pointed by source (including the null character) to the destination.

2. **strncpy**: A standard function that copies up to n characters from the string pointed by source to the destination. If the source string length is less than n, the remainder of the destination will be padded with null characters.

3. **str_is_alpha**: A custom function that checks if a string contains only alphabetic characters. It might return 1 if true and 0 if false.

4. **str_is_numeric**: A custom function that checks if a string contains only numeric characters. It might return 1 if true and 0 if false.

5. **str_is_lowercase**: A custom function that checks if a string contains only lowercase alphabetic characters. It might return 1 if true and 0 if false.

6. **str_is_uppercase**: A custom function that checks if a string contains only uppercase alphabetic characters. It might return 1 if true and 0 if false.

7. **str_is_printable**: A custom function that checks if a string contains only printable characters. It might return 1 if true and 0 if false.

8. **strupcase**: A custom function that converts all the lowercase characters of a string to uppercase.

9. **strlowcase**: A custom function that converts all the uppercase characters of a string to lowercase.

10. **strcapitalize**: A custom function that capitalizes the first letter of each word in a string and makes all other letters lowercase.

11. **strlcpy**:The `strlcpy` function is a string handling function that is used to copy the string from source to destination. It is similar to the `strcpy` function but with a few important differences. 

12. **putstr_non_printable**: A custom function that prints a string, but for non-printable characters, it could print their hexadecimal representation.

13. **print_memory**: A custom function that prints the memory representation of data. This could be used for debugging purposes.

# C 03

1. **strcmp**: A standard function in C, `strcmp` compares two strings and returns an integer less than, equal to, or greater than zero if the first string (str1) is found, respectively, to be less than, to match, or be greater than the second string (str2). The comparison is done lexicographically.

2. **strncmp**: The `strncmp` function is similar to `strcmp` but it compares up to n characters. Comparisons between strings of unequal length that match up to the end of the shorter string will result in a positive or negative value (depending on whether the longer string is greater or less, respectively).

3. **strcat**: The `strcat` function in C is used to concatenate or join two strings. It appends the source string at the end of the destination string. The resulting string is null-terminated.

4. **strncat**: `strncat` is a function in C that appends the first n characters of the source string to the destination string, also ensuring the resulting string is null-terminated.

5. **strstr**: `strstr` is a function that finds the first occurrence of the substring in the source string. It returns a pointer to the first occurrence in the source string, or NULL if the substring is not found.

6. **strlcat**: `strlcat` is similar to `strncat`, but it is safer because it takes the total length of the destination buffer, and ensure it does not overrun the size of the buffer. It's mainly used in a BSD-style operating system like FreeBSD, OpenBSD, etc., but not in standard C library.


# C 04

1. **strlen**: The `strlen` function in C returns the length of a given string. The length of a string is determined by the terminating null-character: A C string is as long as the number of characters between the beginning of the string and the terminating null character.

2. **putstr**: `putstr` is not a standard C function but is often seen in educational contexts and some libraries. It is generally used to print a string to the standard output (usually the terminal). It takes a string as an argument and doesn't return any value.

3. **putnbr**: Similar to `putstr`, `putnbr` is not a standard C function but is often used in educational contexts. It is typically used to print an integer to the standard output. It takes an integer as an argument and doesn't return any value.

4. **atoi**: The `atoi` function in C takes a string (which represents an integral number) as an argument and returns its value as an int. If the input string begins with whitespace, it is ignored. If the string cannot be converted into an integer, it returns zero.

5. **putnbr_base**: `putnbr_base` is also not a standard C function but might be used in some educational contexts or libraries. It is typically used to print an integer to the standard output in a specified base. It takes an integer and a string representing the base as arguments. For instance, for binary output, the base string would be "01".

6. **atoi_base**: Similar to `putnbr_base`, `atoi_base` is not a standard C function but might be used in some contexts. It converts a string, which represents an integer in a certain base, into an int value. It takes a string and the base as arguments. For example, if the string is "1010" and the base is "01", it would return the decimal number 10.

# C 05

1. **iterative_factorial**: This is not a standard C function, but a factorial function implemented using a loop (iteratively). It calculates the factorial of a number (n!) by multiplying all positive integers less than or equal to the input number.

2. **recursive_factorial**: This is a factorial function implemented using recursion. It calculates the factorial of a number by calling itself with decreasing values until it reaches the base case, typically 0 or 1, where it returns 1.

3. **iterative_power**: Again, not a standard C function, but it calculates the power of a number iteratively. For example, `iterative_power(2, 3)` will calculate `2*2*2`.

4. **recursive_power**: This function calculates the power of a number using recursion. It multiplies the base number by the result of the function called with a decreased exponent until the exponent is 0, at which point it returns 1.

5. **fibonacci**: This function, typically implemented either iteratively or recursively, generates the Fibonacci sequence, in which each number is the sum of the two preceding ones, starting from 0 and 1.

6. **sqrt**: The `sqrt` function in C returns the square root of a given number. If the argument passed is negative, it will return a domain error.

7. **is_prime**: This function checks if a number is a prime number (a number greater than 1 that has no divisors other than 1 and itself). It usually does this by checking divisibility up to the square root of the number.

8. **find_next_prime**: This function finds the next prime number after the given number. It does this by starting at the number given plus one and checking each subsequent number to see if it's prime, stopping when it finds a prime number.

# C 06

1. **print_program_name**: This function prints the name of the program. In C, when a program is run, the first argument (argv[0]) is always the name of the program. So, this function might print argv[0].

2. **print_params**: This function prints the parameters or arguments passed to the program. In a C program, these are accessed through the argv array, which starts from argv[1] to argv[argc-1].

3. **rev_params**: This function prints the parameters or arguments passed to the program in reverse order. It would start from argv[argc-1] and go down to argv[1].

4. **sort_params**: This function sorts the parameters or arguments passed to the program. It could use a sorting algorithm (like bubble sort, quick sort, etc.) to sort the argv array from argv[1] to argv[argc-1] and then print the sorted parameters.

# C 07

1. **strdup**: This function would create a copy of a given string by dynamically allocating memory (using `malloc` or similar) and then copying the string into the new memory location.

2. **range**: This function create an array of sequential integers within a given range. For instance, `range(1,5)` could produce an array `[1, 2, 3, 4, 5]`.

3. **ultimate_range**: This function be an extension of `range`, potentially returning more information such as the size of the range or allowing for steps other than 1.

4. **strjoin**: This function concatenates two strings. It might allocate memory for a new string that contains the contents of both input strings one after the other.

5. **convert_base**: This function convert a number from one base to another. For example, it could be used to convert a binary number to a decimal number or a decimal number to hexadecimal.

6. **split**: This function splits a string into an array of strings based on a given delimiter. For example, `split("hello world", " ")` could return an array with two elements: `["hello", "world"]`.

# C 08

1. **.h**: In C programming, .h refers to a header file. Header files usually contain function declarations, macro definitions, and other necessary constructs references across multiple source files.

2. **boolean.h**: This would typically be a header file that includes the definition of a Boolean data type. Standard C does not have a boolean type, but C99 includes a `_Bool` type, and a `bool` macro is included in the `stdbool.h` header file.

3. **abs.h**: This is not a standard C header file. It is likely user-defined. The name suggests it might contain the declaration of a function for computing the absolute value of a number.

4. **point.h**: Again, this is not a standard C header file. The name suggests it might define a Point structure or related functions for handling points, perhaps in a 2D space.

5. **strs_to_tab**: This is not a standard C function. Based on the name, it likely converts a string or multiple strings into a table or array structure, but the specifics would depend on how the function is implemented.

6. **show_tab**: This is also not a standard C function. It probably prints the contents of a table or array to the console, but again, the specifics would depend on the function's implementation.

# C 09

1. **libft**: In the context of C programming, "libft" is often used to refer to a user-created library of useful functions that a programmer has built to use in multiple programs. For example, it might contain custom versions of functions like `strlen`, `strcpy`, etc. The name "libft" seems to originate from 42 School's project, where students are asked to recreate various standard C library functions.

2. **Makefile**: A Makefile is a file used by the "make" build automation tool to control the compilation of a program. It consists of rules and dependencies that specify how to derive the target program from the source files. When you run the "make" command, it looks for a Makefile in the current directory and follows its instructions to build your project.

3. **split**: In C programming, "split" would typically refer to a function that splits a string into multiple substrings based on a delimiter. C standard library does not include a split function, so this would be a user-defined function. The exact implementation could vary, but generally, the function would take as input a string and a delimiter, and return an array of substrings.

# C 10

1. **display_file**: This term usually refers to a C program or function that opens and reads a file, then prints its contents to the console. This could be implemented using functions such as `fopen`, `fread`, and `printf` from the standard library.

2. **cat**: This term is most often used to refer to the Unix `cat` command, which concatenates and displays files. If implemented in a C program, a `cat` function would read one or more files and write their contents to the standard output (typically the console). It could be implemented using similar functions to `display_file`.

3. **tail**: The `tail` command in Unix/Linux displays the last part of a file. In the context of C programming, this could be a function or program that reads a file and prints the last `n` lines to the console. This could be implemented by reading the file into a buffer and then printing the last `n` lines from the buffer.

4. **hexdump**: A hexdump is a hexadecimal view (base-16) of data. A `hexdump` function or program in C would read data (typically from a file), and then output the data in a formatted hexadecimal representation. This is often used in debugging, reverse-engineering, and when working with binary files or network data. This could be implemented using file reading functions like `fopen` and `fread`, and then printing each byte in hexadecimal format with `printf`.

# C 11

1. **foreach**: While there's no built-in `foreach` keyword in C like in some other languages, this term usually refers to a programming pattern where you iterate over each item in a collection such as an array or list. This is typically done with a `for` or `while` loop in C.

2. **map**: `map` isn't a built-in function in C, but it generally refers to a function that applies a given function to every element of a collection, such as an array. The result is a new collection containing the results of applying the function to each element of the original collection.

3. **any**: This term usually refers to a function that checks if any element of a collection satisfies a certain condition. It typically takes a predicate function as an argument (a function returning a boolean value), applies it to each element in the collection, and returns true if the predicate returns true for any element.

4. **count_if**: This function would count the number of elements in a collection that satisfy a given condition or predicate. It would take a collection and a predicate function as arguments, apply the predicate to each element, and increment a counter each time the predicate returns true.

5. **is_sort**: This is likely a function that checks if a collection (like an array) is sorted. It would iterate through the collection and return false if it finds an element that is greater than the following element.

6. **do-op**: This term could refer to a function that performs a specific operation (like addition, subtraction, multiplication, etc.) based on an operator passed as an argument. It would likely take two numerical arguments and a character or string representing the operator.

7. **sort_string_tab**: This function would likely sort an array of strings in lexicographical order. It could be implemented using any sorting algorithm, but the comparison function would need to compare strings (likely using `strcmp` or similar).

8. **advanced_sort_string_tab**: This term could refer to a more advanced or flexible version of `sort_string_tab`. Perhaps it takes a custom comparison function as an argument, allowing the user to define their own sorting criteria.

# C 12

1. **create_elem**: This function would typically initialize a new element for a linked list. It would likely take a value to store in the new element and return a pointer to the newly allocated element.

2. **list_push_front**: This function would add a new element to the beginning of a linked list. It would need to update the head of the list to point to the new element.

3. **list_size**: This function would return the number of elements in a linked list by iterating through the list from the head to the end.

4. **list_last**: This function would return the last element in a linked list. It would need to iterate through the list until it finds an element with no next element.

5. **list_push_back**: This function would add a new element to the end of a linked list. It would need to find the current last element and update its next pointer to point to the new element.

6. **list_push_strs**: This function would likely take an array of strings and add each string as a new element in a linked list.

7. **list_clear**: This function would remove all elements from a linked list, freeing any associated memory.

8. **list_at**: This function would return the element at a specific index in a linked list.

9. **list_reverse**: This function would reverse the order of elements in a linked list.

10. **list_foreach**: This function would apply a function to each element in a linked list.

11. **list_foreach_if**: This function would apply a function to each element in a linked list that satisfies a certain condition.

12. **list_find**: This function would find the first element in a linked list that satisfies a certain condition.

13. **list_remove_if**: This function would remove all elements from a linked list that satisfy a certain condition.

14. **list_merge**: This function would merge two linked lists into a single linked list.

15. **list_sort**: This function would sort the elements of a linked list according to a given comparison function.

16. **list_reverse_fun**: This function would apply a function to each element of a linked list in reverse order.

17. **sorted_list_insert**: This function would insert a new element into the correct position in a sorted linked list to maintain the list's sorted order.

18. **sorted_list_merge**: This function would merge two sorted linked lists into a single sorted list.

# C 13

1. **btree_create_node**: This function is typically used to initialize a new node in a binary tree. The function might take a data value as an argument, allocate memory for a new node, set the data value, and initialize the left and right child pointers to null. The function would then return a pointer to the new node.

2. **btree_apply_prefix**: This function is likely used to traverse a binary tree in a prefix (or pre-order) manner. In a prefix traversal, the function would first visit the current node, then recursively visit the left child and the right child. The "apply" in the function name suggests that a provided function would be applied to the data in each node as it is visited.

3. **btree_apply_infix**: This function is probably used to traverse a binary tree in an infix (or in-order) manner. In an infix traversal, the function would first recursively visit the left child, then visit the current node, and finally recursively visit the right child. As with `btree_apply_prefix`, the provided function would be applied to the data in each node.

4. **btree_apply_suffix**: This function likely traverses a binary tree in a suffix (or post-order) manner. In a suffix traversal, the function would first recursively visit the left child and the right child, and then visit the current node. The provided function would be applied to the data in each node.

5. **btree_insert_data**: This function would insert a new node into a binary tree. The precise behavior would depend on the type of the binary tree. For a binary search tree, the function would place the new node such that all nodes to its left have smaller values and all nodes to its right have larger values.

6. **btree_search_item**: This function would search for a node with a specific value in a binary tree. If the tree is a binary search tree, the function might use the property of binary search trees that allows it to skip over large parts of the tree while searching.

7. **btree_level_count**: This function is expected to return the number of levels or the height of a binary tree. Level 11 suggests that it's referring to the 11th level in the tree.

8. **btree_apply_by_level**: This function would traverse a binary tree level by level (a breadth-first traversal) and apply a provided function to the data in each node. This might be used, for example, to print the data in the nodes level by level.


# Data types

There are several data types, which can be grouped into the following categories:

1. **Primary (Built-in) Data Types:**
   - `int`: To store integer values.
   - `float`: To store decimal numbers.
   - `double`: To store large decimal numbers.
   - `char`: To store a single character.
   - `void`: Special purpose type without any value.

2. **Derived Data Types:**
   - `array`: To store multiple values of the same type.
   - `function`: Used to create functions.
   - `pointer`: For storing address of variables.

3. **Enumeration types:**
   - `enum`: For user defined data types.

4. **User Defined Data Types:**
   - `struct`: To create a data type that can contain other data types.
   - `union`: Similar to struct but it can store only one variable at a time.

Each of these data types requires different amounts of memory, and they have specific operations that can be performed on them.

# Special Characters

In C programming, several characters and character sequences are used with special meanings, often referred to as symbols or operators. Here's a list of most commonly used characters and their typical meanings:

1. **()**: Parentheses are used for function calls and declarations, grouping in expressions, and to specify the condition in control flow structures.

2. **{}**: Braces are used to define blocks of code, such as function or control flow structures.

3. **;**: Semicolon is used to terminate statements.

4. **' '**: Single quotes define character constants.

5. **" "**: Double quotes define string literals.

6. **#**: Used for preprocessor directives, like `#include` and `#define`.

7. **,**: Comma is used as a separator, e.g., in function arguments and in multiple declarations/assignments.

8. **&**: Ampersand is used for the "address of" operator and also as a bitwise AND operator.

9. **|**: The pipe symbol is used as a bitwise OR operator.

10. **^**: The caret is used as a bitwise XOR operator.

11. **~**: Tilde is used as a bitwise NOT operator.

12. **\***: Asterisk is used for declaring pointers, dereferencing pointers, and multiplication.

13. **/**: Forward slash is used for comments (when followed by another slash) and division.

14. **\\**: Backslash is used for escape sequences in character and string literals.

15. **->**: Arrow operator is used to access members of a structure or union via a pointer.

16. **.**: Dot is used to access members of a structure or union.

17. **[]**: Square brackets are used for array indexing.

18. **<>**: Angle brackets are used with `#include` to specify system header files.

19. **-**: Minus sign is used for subtraction/negation and also to denote a negative number.

20. **+**: Plus sign is used for addition and to denote a positive number.

21. **>** and **<**: Greater than and less than comparison operators.

22. **>=** and **<=**: Greater than or equal to and less than or equal to operators.

23. **==**: Equality operator.

24. **!=**: Not equal to operator.

25. **&&**: Logical AND operator.

26. **||**: Logical OR operator.

27. **!**: Logical NOT operator.

28. **++** and **--**: Increment and decrement operators.

29. **%**: Modulus operator.

30. **? :**: Ternary conditional operator.

31. **=**: Assignment operator.

32. **+=, -=, *=, /=, %=, >>=, <<=, &=, ^=, |=**: Compound assignment operators.

33. **<< and >>**: Bitwise shift operators.

Note: The meaning of these characters can change depending on the context. For example, `*` can be used for multiplication in an arithmetic expression, to declare a pointer variable, or to dereference a pointer.

# Common format specifiers

- `%d` or `%i`: Used for signed decimal integers. Example: `printf("%d", 5);` prints `5`.
- `%u`: Used for unsigned decimal integers. Example: `printf("%u", -5);` prints `4294967291` (on a system with 32-bit integers).
- `%f`: Used for floating-point values. Example: `printf("%f", 3.14);` prints `3.140000`.
- `%s`: Used for strings. Example: `printf("%s", "Hello");` prints `Hello`.
- `%c`: Used for characters. Example: `printf("%c", 'A');` prints `A`.
- `%x` or `%X`: Used for unsigned hexadecimal integers (lowercase and uppercase). Example: `printf("%x", 255);` prints `ff`.
- `%o`: Used for octal (base 8) values. Example: `printf("%o", 8);` prints `10`.
- `%e` or `%E`: Used for scientific notation (lowercase and uppercase). Example: `printf("%e", 300.5);` prints `3.005000e+02`.
- `%g` or `%G`: Used for shorter of `%f` and `%e` (lowercase and uppercase). Example: `printf("%g", 300.5);` prints `300.5`.
- `%p`: Used for pointer address. Example: `int x; printf("%p", &x);` prints the address of `x`.
- `%hd` and `%hi`: Used for `short int` (signed).
- `%hu`: Used for `unsigned short int`.
- `%ld` and `%li`: Used for `long int` (signed).
- `%lu`: Used for `unsigned long int`.
- `%lld` and `%lli`: Used for `long long int` (signed).
- `%llu`: Used for `unsigned long long int`.
- `%f`, `%lf`, `%Lf`: Used for `float`, `double`, and `long double` respectively.
- `%a` and `%A`: Used for hexadecimal floating-point number.
- `%n`: Used to get the number of characters written so far.
- `%hhX`, `%hX`, `%lX`, `%llX`: Used for `unsigned char`, `unsigned short int`, `unsigned long int` and `unsigned long long int` as uppercase hexadecimal.
- `%hhx`, `%hx`, `%lx`, `%llx`: Same as above but for lowercase hexadecimal.
- `%ho`, `%hho`, `%lo`, `%llo`: Used for `unsigned short int`, `unsigned char`, `unsigned long int`, and `unsigned long long int` as octal.

You can also modify these with various flags and field widths:

- `%-10d`: Left-justify the integer in a field of width 10. Example: `printf("%-10d", 5);` prints `5         `.
- `%08d`: Pad the integer with zeroes to fill a field of width 8. Example: `printf("%08d", 123);` prints `00000123`.
- `%.2f`: Print a floating point number with 2 digits after the decimal point. Example: `printf("%.2f", 3.14159);` prints `3.14`.

Additionally, there are a few specifiers that are used with non-standard types:

- `%zu`: Used for `size_t`.
- `%zd`: Used for `ssize_t`.
- `%tX`, `%tx`: Used for `ptrdiff_t` as hexadecimal (uppercase and lowercase respectively).
- `%to`: Used for `ptrdiff_t` as octal.

It's also worth noting that the exact behavior of these format specifiers can depend on the system and compiler you're using. Always consult your compiler's documentation to make sure you're using the right format specifier for your needs.







