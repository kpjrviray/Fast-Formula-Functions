# Function Name: INSTR

### Usage:
Indicates if a string is a substring
<br><br>

### Compatible Module(s):
All
<br><br>

### Signature(s):
```
INSTR( String STR1, String STR2 )
```
**Usage:** Checks if `STR2` is a substring of `STR1` staring at the first character of each string.<br>
**Optional Parameters:**<br>
**Return Type:** `Number`<br>
**Required Context:**<br>
<br>

```
INSTR( String STR1, String STR2, Number N, Number M )
```
**Usage:** Searches `STR1` at the `N`'th character for the `M`'th occurence of `STR2`. <br>
**Optional Parameters:** `Number NUM2`<br>
**Return Type:** `Number`<br>
Returns the location of `STR2` within `STR1` or returns 0 if the function does not find a match.<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
`position` is the location where `delimiter` is located in `inputString`.
```
position =  INSTR(inputString, delimiter, 1, 1)
```