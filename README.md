Basic Arithmetic operations class for python
================================



A python class for basic arithmetic operations. The class can be used for:

* add
* subtract
* divide
* multiply


Quick Start
---------------------

<pre>
# import rational from arithmetic module

from arithmetic import Rational
rational = Rational()

# add 4 and 2
print rational.add(4, 2)

# subtract 2 from 6
print rational.subtract(6, 2)

# divide 100 by 10
print rational.divide(100, 10)   

# multiply 3 by 7
print rational.multiply(3, 7)
</pre>

 
Running Tests
---------------------

<pre>
$ python tests.py -v

Test Outcomes
testAdd (__main__.TestArithmetic) ... ok
testDivide (__main__.TestArithmetic) ... ok
testMultipy (__main__.TestArithmetic) ... ok
testSubtract (__main__.TestArithmetic) ... ok

----------------------------------------------------------------------
Ran 4 tests in 0.000s

OK
</pre>
