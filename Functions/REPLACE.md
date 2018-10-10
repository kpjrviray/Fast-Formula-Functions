# Function Name: REPLACE

### Usage:
Replace or remove substrings from a string.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
REPLACE( String EXPR, String SEARCH, String REPLACEMENT )
```
**Usage:** Returns the text string operand EXPR with every occurrence of SEARCH replaced with REPLACEMENT. If REPLACEMENT is omitted, it removes all occurrences of SEARCH. Use REPLACE to substitute one string for another or to remove character strings.<br>
**Optional Parameters:** String REPLACEMENT<br>
**Return Type:** String<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, the `J` in `JACK AND JUE` was replaced with `BL`, converting the string to `BLACK AND BLUE`.
```
/* Set A to 'BLACK and BLUE'. */
A = REPLACE('JACK and JUE', 'J', BL')
```