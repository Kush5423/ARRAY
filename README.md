# ARRAY
In C++, an array is a variable that can store multiple values of the same type. For example,

Suppose a class has 27 students, and we need to store the grades of all of them. Instead of creating 27 separate variables, we can simply create an array:

double grade[27];
Here, grade is an array that can hold a maximum of 27 elements of double type.

In C++, the size and type of arrays cannot be changed after its declaration.

C++ Array Declaration
dataType arrayName[arraySize];
For example,

int x[6];
Here,

int - type of element to be stored
x - name of the array
6 - size of the array
Access Elements in C++ Array
In C++, each element in an array is associated with a number. The number is known as an array index. We can access elements of an array by using those indices.

// syntax to access array elements
array[index];
