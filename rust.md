- **Decimal integer** `0|[1-9]([_']?[0-9])*`  
  Allows for separators between digits (separators can't be adjacent).
  Literals can't start with 0 if they don't equal 0.  
  Separators are `_` and `'` and can be used interchangeably.
- **Binary integer** `0[bB][10]([_']?[01])*`
- **Octal integer** `0[oO][0-7]([_']?[0-7])*`
- **Hexadecimal integer** `0[xX][0-9a-fA-F]([_']?[0-9a-fA-F])*`
- **Hexadecimal floating point** `0[xX][0-9a-fA-F]([_']?[0-9a-fA-F])*(\.[0-9a-fA-F]*)?[pP][+-]?(0|[1-9][0-9]*)`  
  No separators in either fractional and exponent segments.
