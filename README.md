Math_Quaternion
===============

A package of classes that represent and manipulate quaternions. 

Contains definitions for basic arithmetic functions in a static class.

Quaternions are an extension of the idea of complex numbers, and
are defined as: 
    q = a + b*i + c*j + d*k
    
In 1844 Hamilton described a system in which numbers were composed of
a real part and 3 imaginary and independent parts (i,j,k), such that:
    1. i^2 = j^2 = k^2 = -1
    2. ij = k, jk = i, ki = j
    3. ji = -k, kj = -i, ik = -j

These are known as "Hamilton's rules"

This is old code I wrote for [PEAR](http://pear.php.net). 
Originally it was tracked in CVS, then it was moved to SVN, 
and now I am importing it to git :-)

-- Jesus M. Castagnetto
