
PCAP certification

------

The rfind() and index() methods in Python are used to find the position of a substring within a string. However, there are differences in how they handle certain situations:

rfind(substring):

The rfind() method searches for the last occurrence of the specified substring ("Hell") within the string (strng).
If the substring is found, rfind() returns the index of the last occurrence of the substring in the string. If the substring is not found, it returns -1.
In your example, strng.rfind("Hell") returns 0 because "Hell" is found at the beginning of the string.
index(substring):

The index() method searches for the first occurrence of the specified substring ("Hell") within the string (strng).
If the substring is found, index() returns the index of the first occurrence of the substring in the string. If the substring is not found, it raises a ValueError.
In your example, strng.index("Hell") returns 0 because "Hell" is found at the beginning of the string.
In summary:

Both methods return the index of the substring if it is found in the string.
rfind() returns the index of the last occurrence, while index() returns the index of the first occurrence.
If the substring is not found, rfind() returns -1, while index() raises a ValueError.
It's important to choose the appropriate method based on whether you want to find the first occurrence (index()) or the last occurrence (rfind()) of the substring in the string.

The rfind() method finds the last occurrence of a specified value.
The index() method finds the first occurrence of a specified value.

-------
The folder created by Python used to store pyc files is named:
__pycache__

--------

What is the expected output of the following code?
print(type(1J))

<type 'complex'>

--------
