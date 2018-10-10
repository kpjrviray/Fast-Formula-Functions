# Function Name: LTRIM

### Usage:
Return the left most substring of a string.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
LPAD( String EXPR, String SET )
```
**Usage:** Returns the text string operand `EXPR` with all the left-most characters that appear in `SET` removed. The default for `SET` is a blank. If none of the left-most characters of `EXPR` appear in `SET`, then LTRIM returns `EXPR`.<br>
**Optional Parameters:** `String SET`<br>
**Return Type:**`String`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `A` is set to `def` becuase LTRIM has removed `abc` from the leftmost side of the input string `abcdef`.
```
/* A is set to 'def' */
A = LTRIM ('abcdef','abc')
```

**Usage:**<br>
In the example below, the return value stays the same because `bc` is not part of the leftmost input string `abcdef`.
```
/* A is set to 'abcdef' */
A = LTRIM ('abcdef','bc')
```