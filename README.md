bc extensions
=============


bc is a powerful, yet somewhat minimalistic "basic calculator'
for *ix environments. It is a pure command line tool which offers
floating point arithmetics of arbitrary precision aa well as large
number arithmetics. For further information on bc, visit
[https://www.gnu.org/software/bc/manual/html_mono/bc.html](GNU bc's documentations)

These files can be "imported" in bc by passing them to bc on the
command line. Make sure, the .l` flag is set:

    bc -l extensions.bc scientific_constants.bc

Features
--------

**I	constants**

1.	pi			:	defined as 4*atan(1)
2.	e			:	defined as e(1)

**II	trigonometry**

1.	sin(x)			:	returns sine of x
2.	cos(x)			:	returns cosine of x
3.	atan(x)			:	returns arc tangent of x
4.	tan(x)			:	returns tangent of x
5.	asin(x)			:	returns arc sine of x
6.	acos(x)			:	returns arc cosine of x
7.	cot(x)			:	returns cotangent of x
8.	acot(x)			:	returns arc cotangent of x
9.	sec(x)			:	returns secans of x
10.	cosec(x),csc(x)		:	returns cosecans of x
11.	asec(x)			:	returns arc secans of x
12.	acosec(x),ascs(x)	:	returns arc cosecans of x
13.	sinh(x)			:	returns hyperbolical sine of x
14.	cosh(x)			:	returns hyperbolical cosine of x
15.	tanh(x)			:	returns hyperbolical tangent of x
16.	coth(x)			:	returns hyperbolical cotangent of x
17.	asinh(x)		:	returns arc hyperbolical sine of x
18.	acosh(x)		:	returns arc hyperbolical cosine of x
19.	atanh(x)		:	returns arc hyperbolical tangent of x
20.	acoth(x)		:	returns arc hyperbolical cotangent of x
21.	sech(x)			:	returns secans hyperbolicus of x
22.	cosech(x),csch(x)	:	returns cosecans hyperbolicus of x
23.	asech(x)		:	returns arc secans hyperbolicus of x
24.	acosech(x),acsch(x)	:	returns arc cosecans hyperbolicus of x


**III	exponential functions**

1.	ln(x)			:	returns natural logarithm of x
2.	log(x)			:	returns logarithm (base 10) of x
3.	lb(x),ld(x)		:	returns logarithm (base 2) of x
4.	pow(x,y)		:	returns x to the power of y

**IV number theory**

1.	abs(n)			:	returns absolute value of n
2.	mod(a,b)		:	returns a modulo b
3.	factorize(n),fac(n)	:	prints primefactors of n;
					returns number of primefactors;
					returns 0 if n is a prime number;
					returns -1 if n is +-1 or 0.
					CAUTION: 13-digit number may need 30 s
4.	factorial(n),f(n)	:	returns n factorial
5.	gcd(a,b)		:	returns the greatest common divisor of a and b
6.	lcm(a,b)		:	returns the least common multiple of a and b
7. bessel(n,x)			:	returns the Bessel function order n of x
