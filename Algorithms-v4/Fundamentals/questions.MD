### 1.1.6 What does the following program print?
```
int f = 0;
int g = 1;
for (int i = 0; i <= 15; i++) {
	f = f + g;
	g = f - g;
}
```
### 1.1.9 Write a code fragment that puts the binary representation of a positive integer N into a String s.

### 1.1.13 Write a code fragment to print the transposition (rows and columns changed) of a two-dimensional array with M rows and N columns.

### 1.1.14 Write a method lg() that takes an int value N as argument and returns the largest int not larger than the base-2 logarithm of N. Do not use the library.

### 1.1.15 Write a static method histogram() that takes an array a[] of int values and an integer M as arguments and returns an array of length M whose ith entry is the number of times the integer i appeared in the argument array. If the values in a[] are all between 0 and M-1, the sum of the values in the returned array should be equal to a.length.

### 1.1.16 Give the value of exR1(6):
```
public static String exR1(int n) {
	if (n <= 0) return "";
	return exR1(n-3) + n + exR1(n-2) + n;
}
```
