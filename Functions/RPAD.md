# Function Name: RPAD

### Usage:
Add padding text to a string or get a substring of a string starting from the right side.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
RPAD( String EXPR, Number N, Number PAD )
```
**Usage:** Returns the text string operand `EXPR` right-padded to length `N` with the sequence of characters in `PAD`. The default value for `PAD` is a blank. If `EXPR` is longer than `N`, then LPAD returns the portion of `EXPR` that fits in n.
<br>
**Optional Parameters:** `Number PAD`<br>
**Return Type:**<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `A` is set to `helloXYXYX`. `XY` is appedned to the right of `hello` until `A` becomes `10` characters long. Hence why the right padding is `XYXYX`.
```
/* A is set to 'helloXYXYX' */
A = RPAD ('hello, 10, 'XY')
```
<br>

**Usage:**<br>
In the example below, `A` is set to `helloBBBBB`. `B` is appended to the right side of `hello` until the string is `10` characters long.
```
/* A is set to 'helloBBBBB' */
A = RPAD ('hello', 10, 'B')
```
<br>

**Usage:**<br>
In the example below, `A = 'ello'` because if no `PAD` argument is given and `N` is shorter than the input string, will return a substring of the string starting from the right.
```
/* A is set to 'ello' */
A = LPAD ('hello', 4 )
```