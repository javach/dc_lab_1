# uint1024_t

`uint1024_t` represents an unsigned type with fixed 1024 bit size. 
It can represent numbers from 0 to 2^1024 - 1 and supports basic arithmetic operations.

### Functions

`new_uint1024_t()` - creates new `uint1024_t` with value equal to 0.

`from_uint(unsigned int x)` - creates `uint1024_t` with value equal to `x`.

`add_op(uint1024_t x, uint1024_t y)` - creates `uint1024_t` with value equal to `x + y`. If overflow happens, program exits.

`subtr_op(uint1024_t x, uint1024_t y)` - creates `uint1024_t` with value equal to `x - y`. If `x` < `y`, program exits.

`mult_op(uint1024_t x, uint1024_t y)` - creates `uint1024_t` with value equal to `x * y`. If overflow happens, program exits.

`printf_value(uint1024_t x)` - prints hexadecimal representation of  `x`.

`scanf_value(uint1024_t *x)` - scans `stdin` and puts converted value to `x`.