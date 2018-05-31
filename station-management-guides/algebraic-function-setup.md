# Algebraic Function Setup

Algebraic Functions allow you to perform simple to complex math functions using any sensor data as variables and display the resulting calculated data as graphs or tables. Algebraic Functions can also be used in conjunction with a [Virtual Sensor](virtual-sensor-setup.md) to allow the calculated data to be stored and tracked. <span class="app-name"></span> provides numerous predefined formulas for common uses such as unit conversion, flow or weather formulas. You can also create your own custom formulas by utilizing the supported basic or advanced operands listed below. To create an Algebraic Function follow the steps listed below:

### Creating a New Algebraic Function

1.  Navigate to the Station Management page for the station that you want to create the algebraic function for.
2.  On the Station Management page click 'Data Transformations' from the side menu to expand the options and then select 'Algebraic Functions'.
3.  Click the '+ Function' button in the top right corner of the Algebraic Function Summary page.
4.  You can now select whether you would like to create a custom formula or a predefined formula.
    -   If you selected a predefined option, you can now select the appropriate formula from the list of formulas and then click 'Next'.
5.  You will now be taken to the step where you can create or customize your formula. If you selected a predefined formula than the formula field will already be filled in. If you selected 'Custom Formula' in the first step than you will now enter your formula in this field and select the appropriate output unit from the list. Note that you can also edit a predefined formula.
6.  For each variable in your formula, select the parameter that you would like to assign to that particular variable.
7.  Give your Algebraic Function a unique name to identify it by and provide a description of its purpose.
8.  Click the 'Save' button to create your new Algebraic Function.
9.  You should now see your new Algebraic Function display on a card on the Algebraic Function Summary page.

### Basic Operands

-   \+ – Plus
-   \- – Minus
-   \* – Times
-   / – Division
-   ^ – Exponent

### Advanced Operands

In addition to the basic operands, you can use any of the following:

-   sin(x) – Sine of x (x is in radians)
-   cos(x) – Cosine of x (x is in radians)
-   tan(x) – Tangent of x (x is… well, you know)
-   asin(x) – Arc sine of x (in radians)
-   acos(x) – Arc cosine of x (in radians)
-   atan(x) – Arc tangent of x (in radians)
-   sinh(x) – Hyperbolic sine of x (x is in radians)
-   cosh(x) – Hyperbolic cosine of x (x is in radians)
-   tanh(x) – Hyperbolic tangent of x (x is… well, you know)
-   asinh(x) – Hyperbolic arc sine of x (in radians)
-   acosh(x) – Hyperbolic arc cosine of x (in radians)
-   atanh(x) – Hyperbolic arc tangent of x (in radians)
-   sqrt(x) – Square root of x. Result is NaN (Not a Number) if x is negative
-   log(x) – Natural logarithm of x (not base-10)
-   abs(x) – Absolute value (magnitude) of x
-   ceil(x) – Ceiling of x — the smallest integer that’s >= x
-   floor(x) – Floor of x — the largest integer that’s <= x
-   round(x) – X, rounded to the nearest integer, using “gradeschool rounding”
-   trunc(x) – Integral part of a X, looks like floor(x) unless for negative number
-   exp(x) – ex (exponential/antilogarithm function with base e) Pre-defined functions
-   random(n) – Get a random number in the range [0, n). If n is zero, or not provided, it defaults to 1
-   fac(n) – n! (factorial of n: “n * (n-1) * (n-2) * … * 2 * 1″)
-   min(a,b,…) – Get the smallest (“minimum”) number in the list
-   max(a,b,…) – Get the largest (“maximum”) number in the list
-   pyt(a, b) – Pythagorean function, i.e. the c in “c2 = a2 + b2“
-   pow(x, y) – This is exactly the same as “x^y”
-   atan2(y, x) – Arc tangent of x/y. i.e. the angle between (0, 0) and (x, y) in radians.
-   hypot(a,b) – The square root of the sum of squares of its arguments.
-   if(c, a, b) – The condition function where c is condition, a is result if c is true, b is result if c is false