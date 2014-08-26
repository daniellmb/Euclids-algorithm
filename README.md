40 byte recursive-based version of the Euclidean algorithm. Euclid's algorithm is used to find the greatest common divisor of 2 numbers (the largest number that divides both of them without leaving a remainder). The Euclidean algorithm is based on the principle that the greatest common divisor of two numbers does not change if the smaller number is subtracted from the larger number.

For illustration, the gcd(1071, 462) is calculated from the equivalent gcd(462, 1071 % 462) = gcd(462, 147). The latter GCD is calculated from the gcd(147, 462 % 147) = gcd(147, 21), which in turn is calculated from the gcd(21, 147 % 21) = gcd(21, 0) = 21.

## License

(The MIT License)

Copyright (c) 2011 Daniel Lamb <dlamb.open.source@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
