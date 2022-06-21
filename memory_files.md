# C Language: memset function
(Initialize Memory Block)
In the C Programming Language, the memset function stores c into the first n characters of the object pointed to by s.

Syntax
The syntax for the memset function in the C Language is:

void *memset(void *s, int c, size_t n);
Parameters or Arguments
s
A pointer to a memory block that will be filled.
c
The value to be stored.
n
The number of characters to be stored.
Returns
The memset function returns s.

Required Header
In the C Language, the required header for the memset function is:

#include <string.h>



# C Language: memcpy function
(Copy Memory Block)
In the C Programming Language, the memcpy function copies n characters from the object pointed to by s2 into the object pointed to by s1. It returns a pointer to the destination.

The memcpy function may not work if the objects overlap.


The syntax for the memcpy function in the C Language is:

void *memcpy(void *s1, const void *s2, size_t n);
Parameters or Arguments
s1
An array where s2 will be copied to.
s2
The string to be copied.
n
The number of characters to copy.
Returns
The memcpy function returns s1.

Required Header
In the C Language, the required header for the memcpy function is:

#include <string.h>


