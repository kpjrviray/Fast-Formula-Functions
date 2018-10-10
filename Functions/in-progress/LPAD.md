# Function Name: LPAD

### Usage:
Add padding text to a string or get a substring of a string starting from the left side.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):

```
LPAD( String EXPR, Number N, Number PAD )
```
**Usage:** Returns the text string operand `EXPR` left-padded to length `N` with the sequence of characters in `PAD`. The default value for `PAD` is a blank. If `EXPR` is longer than `N`, then LPAD returns the portion of `EXPR` that fits in n.
<br>
**Optional Parameters:** `Number PAD`<br>
**Return Type:**<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `A` is set to `XYXYXhello`. `XY` is appedned to to `hello` until `A` becomes `10` characters long. Hence why the left padding is `XYXYX`.
```
/* A is set to 'XYXYXhello' */
A = LPAD ('hello', 10, 'XY')
```
<br>

**Usage:**<br>
In the example below, `A` is set to `BBBBBhello`. `B` is appended to the left side of `hello` until the string is `10` characters long.
```
/* A is set to 'BBBBBhello' */
A = LPAD ('hello', 10, 'B')
```
<br>

**Usage:**<br>
In the example below, `A = 'hell'` because if no `PAD` argument is given and `N` is shorter than the input string, will return a substring of the string starting from the left.
```
/* A is set to 'hell' */
A = LPAD ('hello', 4 )
```