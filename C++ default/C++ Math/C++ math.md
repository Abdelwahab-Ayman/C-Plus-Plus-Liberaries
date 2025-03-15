# `<cmath>` (math.h) - C Numerics Library

The `<cmath>` header (also available as `<math.h>` in C) declares a set of functions to compute common mathematical operations and transformations. These functions are essential for performing numerical computations in C++.

---

## **Functions**

### **Trigonometric Functions**

- **`cos`**
  - Compute cosine of an angle (in radians).
  - **Syntax**: `double cos(double x);`
  - **Example**: `cos(0.0)` returns `1.0`.

- **`sin`**
  - Compute sine of an angle (in radians).
  - **Syntax**: `double sin(double x);`
  - **Example**: `sin(0.0)` returns `0.0`.

- **`tan`**
  - Compute tangent of an angle (in radians).
  - **Syntax**: `double tan(double x);`
  - **Example**: `tan(0.0)` returns `0.0`.

- **`acos`**
  - Compute arc cosine (inverse cosine) of a value.
  - **Syntax**: `double acos(double x);`
  - **Example**: `acos(1.0)` returns `0.0`.

- **`asin`**
  - Compute arc sine (inverse sine) of a value.
  - **Syntax**: `double asin(double x);`
  - **Example**: `asin(0.0)` returns `0.0`.

- **`atan`**
  - Compute arc tangent (inverse tangent) of a value.
  - **Syntax**: `double atan(double x);`
  - **Example**: `atan(0.0)` returns `0.0`.

- **`atan2`**
  - Compute arc tangent with two parameters (y, x).
  - **Syntax**: `double atan2(double y, double x);`
  - **Example**: `atan2(1.0, 1.0)` returns `0.785398` (π/4).

---

This is just a subset of the functions provided by `<cmath>`. The library also includes functions for hyperbolic, exponential, logarithmic, power, rounding, and other mathematical operations. Let me know if you'd like details on more functions! 🚀
# `<cmath>` (math.h) - C Numerics Library

The `<cmath>` header (also available as `<math.h>` in C) provides a wide range of mathematical functions. Below is a detailed breakdown of the **hyperbolic functions**, **exponential and logarithmic functions**, **power functions**, and **error and gamma functions**.

---

## **Hyperbolic Functions**

- **`cosh`**
  - Compute hyperbolic cosine.
  - **Syntax**: `double cosh(double x);`
  - **Example**: `cosh(0.0)` returns `1.0`.

- **`sinh`**
  - Compute hyperbolic sine.
  - **Syntax**: `double sinh(double x);`
  - **Example**: `sinh(0.0)` returns `0.0`.

- **`tanh`**
  - Compute hyperbolic tangent.
  - **Syntax**: `double tanh(double x);`
  - **Example**: `tanh(0.0)` returns `0.0`.

- **`acosh`**
  - Compute area hyperbolic cosine (inverse hyperbolic cosine).
  - **Syntax**: `double acosh(double x);`
  - **Example**: `acosh(1.0)` returns `0.0`.

- **`asinh`**
  - Compute area hyperbolic sine (inverse hyperbolic sine).
  - **Syntax**: `double asinh(double x);`
  - **Example**: `asinh(0.0)` returns `0.0`.

- **`atanh`**
  - Compute area hyperbolic tangent (inverse hyperbolic tangent).
  - **Syntax**: `double atanh(double x);`
  - **Example**: `atanh(0.0)` returns `0.0`.

---

## **Exponential and Logarithmic Functions**

- **`exp`**
  - Compute exponential function (e raised to the power of x).
  - **Syntax**: `double exp(double x);`
  - **Example**: `exp(1.0)` returns `2.71828`.

- **`frexp`**
  - Break a floating-point number into its significand and exponent.
  - **Syntax**: `double frexp(double x, int* exp);`
  - **Example**: `frexp(8.0, &exp)` returns `0.5` and sets `exp` to `4`.

- **`ldexp`**
  - Generate a value from a significand and exponent.
  - **Syntax**: `double ldexp(double x, int exp);`
  - **Example**: `ldexp(0.5, 4)` returns `8.0`.

- **`log`**
  - Compute natural logarithm (base e).
  - **Syntax**: `double log(double x);`
  - **Example**: `log(1.0)` returns `0.0`.

- **`log10`**
  - Compute common logarithm (base 10).
  - **Syntax**: `double log10(double x);`
  - **Example**: `log10(100.0)` returns `2.0`.

- **`modf`**
  - Break a number into fractional and integral parts.
  - **Syntax**: `double modf(double x, double* intpart);`
  - **Example**: `modf(3.14, &intpart)` returns `0.14` and sets `intpart` to `3.0`.

- **`exp2`**
  - Compute binary exponential function (2 raised to the power of x).
  - **Syntax**: `double exp2(double x);`
  - **Example**: `exp2(3.0)` returns `8.0`.

- **`expm1`**
  - Compute exponential minus one (e^x - 1).
  - **Syntax**: `double expm1(double x);`
  - **Example**: `expm1(1.0)` returns `1.71828`.

- **`ilogb`**
  - Compute integer binary logarithm.
  - **Syntax**: `int ilogb(double x);`
  - **Example**: `ilogb(8.0)` returns `3`.

- **`log1p`**
  - Compute logarithm of (1 + x).
  - **Syntax**: `double log1p(double x);`
  - **Example**: `log1p(0.0)` returns `0.0`.

- **`log2`**
  - Compute binary logarithm (base 2).
  - **Syntax**: `double log2(double x);`
  - **Example**: `log2(8.0)` returns `3.0`.

- **`logb`**
  - Compute floating-point base logarithm.
  - **Syntax**: `double logb(double x);`
  - **Example**: `logb(8.0)` returns `3.0`.

- **`scalbn`**
  - Scale significand using floating-point base exponent.
  - **Syntax**: `double scalbn(double x, int n);`
  - **Example**: `scalbn(1.5, 3)` returns `12.0`.

- **`scalbln`**
  - Scale significand using floating-point base exponent (long).
  - **Syntax**: `double scalbln(double x, long n);`
  - **Example**: `scalbln(1.5, 3)` returns `12.0`.

---

## **Power Functions**

- **`pow`**
  - Raise a number to a power.
  - **Syntax**: `double pow(double base, double exponent);`
  - **Example**: `pow(2.0, 3.0)` returns `8.0`.

- **`sqrt`**
  - Compute square root.
  - **Syntax**: `double sqrt(double x);`
  - **Example**: `sqrt(16.0)` returns `4.0`.

- **`cbrt`**
  - Compute cubic root.
  - **Syntax**: `double cbrt(double x);`
  - **Example**: `cbrt(27.0)` returns `3.0`.

- **`hypot`**
  - Compute hypotenuse of a right-angled triangle.
  - **Syntax**: `double hypot(double x, double y);`
  - **Example**: `hypot(3.0, 4.0)` returns `5.0`.

---

## **Error and Gamma Functions**

- **`erf`**
  - Compute error function.
  - **Syntax**: `double erf(double x);`
  - **Example**: `erf(0.0)` returns `0.0`.

- **`erfc`**
  - Compute complementary error function.
  - **Syntax**: `double erfc(double x);`
  - **Example**: `erfc(0.0)` returns `1.0`.

- **`tgamma`**
  - Compute gamma function.
  - **Syntax**: `double tgamma(double x);`
  - **Example**: `tgamma(5.0)` returns `24.0`.

- **`lgamma`**
  - Compute log-gamma function.
  - **Syntax**: `double lgamma(double x);`
  - **Example**: `lgamma(5.0)` returns `log(24.0)`.

# `<cmath>` (math.h) - C Numerics Library

The `<cmath>` header (also available as `<math.h>` in C) provides a wide range of mathematical functions. Below is a detailed breakdown of the **rounding and remainder functions**, **floating-point manipulation functions**, **minimum, maximum, and difference functions**, and **other functions**.

---

## **Rounding and Remainder Functions**

- **`ceil`**
  - Round up a value to the nearest integer.
  - **Syntax**: `double ceil(double x);`
  - **Example**: `ceil(3.14)` returns `4.0`.

- **`floor`**
  - Round down a value to the nearest integer.
  - **Syntax**: `double floor(double x);`
  - **Example**: `floor(3.14)` returns `3.0`.

- **`fmod`**
  - Compute the remainder of division of two floating-point numbers.
  - **Syntax**: `double fmod(double x, double y);`
  - **Example**: `fmod(10.5, 3.0)` returns `1.5`.

- **`trunc`**
  - Truncate a value (remove fractional part).
  - **Syntax**: `double trunc(double x);`
  - **Example**: `trunc(3.14)` returns `3.0`.

- **`round`**
  - Round a value to the nearest integer.
  - **Syntax**: `double round(double x);`
  - **Example**: `round(3.5)` returns `4.0`.

- **`lround`**
  - Round a value to the nearest integer and cast to `long`.
  - **Syntax**: `long lround(double x);`
  - **Example**: `lround(3.5)` returns `4`.

- **`llround`**
  - Round a value to the nearest integer and cast to `long long`.
  - **Syntax**: `long long llround(double x);`
  - **Example**: `llround(3.5)` returns `4`.

- **`rint`**
  - Round a value to the nearest integral value using the current rounding mode.
  - **Syntax**: `double rint(double x);`
  - **Example**: `rint(3.5)` returns `4.0`.

- **`lrint`**
  - Round a value to the nearest integral value and cast to `long`.
  - **Syntax**: `long lrint(double x);`
  - **Example**: `lrint(3.5)` returns `4`.

- **`llrint`**
  - Round a value to the nearest integral value and cast to `long long`.
  - **Syntax**: `long long llrint(double x);`
  - **Example**: `llrint(3.5)` returns `4`.

- **`nearbyint`**
  - Round a value to the nearest integral value without raising floating-point exceptions.
  - **Syntax**: `double nearbyint(double x);`
  - **Example**: `nearbyint(3.5)` returns `4.0`.

- **`remainder`**
  - Compute the remainder of division (IEC 60559 compliant).
  - **Syntax**: `double remainder(double x, double y);`
  - **Example**: `remainder(10.5, 3.0)` returns `-0.5`.

- **`remquo`**
  - Compute the remainder and quotient of division.
  - **Syntax**: `double remquo(double x, double y, int* quo);`
  - **Example**: `remquo(10.5, 3.0, &quo)` returns `-0.5` and sets `quo` to `3`.

---

## **Floating-Point Manipulation Functions**

- **`copysign`**
  - Copy the sign of one value to another.
  - **Syntax**: `double copysign(double x, double y);`
  - **Example**: `copysign(3.0, -1.0)` returns `-3.0`.

- **`nan`**
  - Generate a quiet NaN (Not-a-Number) value.
  - **Syntax**: `double nan(const char* tagp);`
  - **Example**: `nan("1")` returns a NaN value.

- **`nextafter`**
  - Compute the next representable value after `x` in the direction of `y`.
  - **Syntax**: `double nextafter(double x, double y);`
  - **Example**: `nextafter(1.0, 2.0)` returns the next representable value greater than `1.0`.

- **`nexttoward`**
  - Compute the next representable value after `x` in the direction of `y` (with `y` as `long double`).
  - **Syntax**: `double nexttoward(double x, long double y);`
  - **Example**: `nexttoward(1.0, 2.0)` returns the next representable value greater than `1.0`.

---

## **Minimum, Maximum, and Difference Functions**

- **`fdim`**
  - Compute the positive difference between two values.
  - **Syntax**: `double fdim(double x, double y);`
  - **Example**: `fdim(5.0, 3.0)` returns `2.0`.

- **`fmax`**
  - Compute the maximum of two values.
  - **Syntax**: `double fmax(double x, double y);`
  - **Example**: `fmax(3.0, 5.0)` returns `5.0`.

- **`fmin`**
  - Compute the minimum of two values.
  - **Syntax**: `double fmin(double x, double y);`
  - **Example**: `fmin(3.0, 5.0)` returns `3.0`.

---

## **Other Functions**

- **`fabs`**
  - Compute the absolute value of a floating-point number.
  - **Syntax**: `double fabs(double x);`
  - **Example**: `fabs(-3.14)` returns `3.14`.

- **`abs`**
  - Compute the absolute value of an integer.
  - **Syntax**: `int abs(int x);`
  - **Example**: `abs(-5)` returns `5`.

- **`fma`**
  - Compute a fused multiply-add operation (x * y + z).
  - **Syntax**: `double fma(double x, double y, double z);`
  - **Example**: `fma(2.0, 3.0, 4.0)` returns `10.0`.

---

This is a comprehensive list of functions provided by `<cmath>`. Let me know if you need further details or examples! 🚀
