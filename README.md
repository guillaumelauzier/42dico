# 42dico

Function names used in C programming ordered by 42Lausanne exercices.


# C 00

1. **putchar**: This function likely takes a single character as an argument and prints it to the standard output. It's similar to the standard C function `putchar()`.

2. **print_alphabet**: This function probably prints the English alphabet ('a' to 'z' or 'A' to 'Z') to the standard output.

3. **print_reverse_alphabet**: This function likely prints the English alphabet in reverse order ('z' to 'a' or 'Z' to 'A') to the standard output.

4. **print_numbers**: This function likely prints the digits (0 to 9) to the standard output.

5. **is_negative**: This function likely takes an integer as an argument and checks if it's negative. It could return a boolean value or print a result to the standard output.

6. **print_comb**: This function likely prints all possible combinations of some set of numbers or characters. The specific set it operates on might be defined within the function or passed as an argument.

7. **print_comb2**: This function is likely a variation of `print_comb`. It might print combinations in a different order or format, or operate on a different set of numbers or characters.

8. **putnbr**: This function likely takes an integer as an argument and prints it to the standard output. It's a common task in C programming.

9. **print_combn**: This function is likely another variation of `print_comb`. It might take an integer 'n' as an argument and print all combinations of 'n' elements from a specific set. 

# C 01

1. **ft**: "ft" usually stands for "function". It is a common prefix used by developers at 42 school network to indicate that a function is a part of their own library, not a standard function from the C library.

2. **ultimate_ft**: Based on the name, this function could be a more advanced or comprehensive version of a function named "ft". Without more information about its functionality, it's hard to be more specific.

3. **swap**: This function probably swaps the values of two variables. It would likely take two pointers to variables as arguments and interchange the values at those memory addresses.

4. **div_mod**: This function likely performs both division and modulo operations. It might take two integer arguments and two pointers to store the results of the division (quotient) and modulo (remainder).

5. **ultimate_div_mod**: This function might be a more advanced or comprehensive version of "div_mod", maybe handling more edge cases or additional functionality.

6. **putstr**: This function probably takes a string as an argument and prints it to the standard output. It's similar to the standard C function `puts()`.

7. **strlen**: This function likely calculates and returns the length of a string. It's similar to the standard C function `strlen()`.

8. **rev_int_tab**: This function probably reverses the order of elements in an integer array.

9. **sort_int_tab**: This function likely sorts an integer array in ascending or descending order.

# C 02

1. **strcpy**: A standard function that copies the string pointed by source (including the null character) to the destination.

2. **strncpy**: A standard function that copies up to n characters from the string pointed by source to the destination. If the source string length is less than n, the remainder of the destination will be padded with null characters.

3. **str_is_alpha**: Likely a custom function that checks if a string contains only alphabetic characters. It might return 1 if true and 0 if false.

4. **str_is_numeric**: Likely a custom function that checks if a string contains only numeric characters. It might return 1 if true and 0 if false.

5. **str_is_lowercase**: Likely a custom function that checks if a string contains only lowercase alphabetic characters. It might return 1 if true and 0 if false.

6. **str_is_uppercase**: Likely a custom function that checks if a string contains only uppercase alphabetic characters. It might return 1 if true and 0 if false.

7. **str_is_printable**: Likely a custom function that checks if a string contains only printable characters. It might return 1 if true and 0 if false.

8. **strupcase**: Likely a custom function that converts all the lowercase characters of a string to uppercase.

9. **strlowcase**: Likely a custom function that converts all the uppercase characters of a string to lowercase.

10. **strcapitalize**: Likely a custom function that capitalizes the first letter of each word in a string and makes all other letters lowercase.

11. **strlcpy 15**: This appears to be a call to the function `strlcpy` with the argument `15`. `strlcpy` is a standard function that copies up to a specified length from the source string to the destination, ensuring null-termination.

12. **putstr_non_printable**: Likely a custom function that prints a string, but for non-printable characters, it could print their hexadecimal representation.

13. **print_memory**: Likely a custom function that prints the memory representation of data. This could be used for debugging purposes.

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

1. **print_program_name**: This function likely prints the name of the program. In C, when a program is run, the first argument (argv[0]) is always the name of the program. So, this function might print argv[0].

2. **print_params**: This function likely prints the parameters or arguments passed to the program. In a C program, these are accessed through the argv array, which starts from argv[1] to argv[argc-1].

3. **rev_params**: This function likely prints the parameters or arguments passed to the program in reverse order. It would start from argv[argc-1] and go down to argv[1].

4. **sort_params**: This function likely sorts the parameters or arguments passed to the program. It could use a sorting algorithm (like bubble sort, quick sort, etc.) to sort the argv array from argv[1] to argv[argc-1] and then print the sorted parameters.

# C 07

1. **strdup**: This function would likely create a copy of a given string by dynamically allocating memory (using `malloc` or similar) and then copying the string into the new memory location.

2. **range**: This function might create an array of sequential integers within a given range. For instance, `range(1,5)` could produce an array `[1, 2, 3, 4, 5]`.

3. **ultimate_range**: This function might be an extension of `range`, potentially returning more information such as the size of the range or allowing for steps other than 1.

4. **strjoin**: This function likely concatenates two strings. It might allocate memory for a new string that contains the contents of both input strings one after the other.

5. **convert_base**: This function might convert a number from one base to another. For example, it could be used to convert a binary number to a decimal number or a decimal number to hexadecimal.

6. **split**: This function could split a string into an array of strings based on a given delimiter. For example, `split("hello world", " ")` could return an array with two elements: `["hello", "world"]`.

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















