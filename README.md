lab4(a):
The Encoding Identifiers are
(1) double average(double*, double&): _Z7averagePdRd
(2) int average(int, float): _Z7averageif

"_Z7averagePdRd": 
"_Z" : prefix
"7"  : 7 characters of "average"
"Pd" : pointer to double
"Rd" : reference to double

 "_Z7averageif":
"_Z" : prefix
"7"  : 7 characters of "average"
"i"  : integer
"f"  : float

=================================================================

lab4(b):
The output in a 64-bit Cygwin environment is:
1 8
4 8
4 8
8 8
This reflects the sizes of the types (char, int, float, double) 
and their pointers in a 64-bit address space.
