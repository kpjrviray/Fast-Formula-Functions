# Function Name: SUBSTR

### Usage:
Returns a substring of a string.
<br><br>

### Compatible Module(s):
All
<br><br>

### Signature(s):

```
SUBSTR( String STR, Number POS, Number LEN )
```
**Usage:** returns a substring of STR that is LEN characters long and starts at the POS location<br>
**Optional Parameters:** Number LEN<br>
**Return Type:** String<br>
**Required Context:**<br>
<br>


### Code Example(s):
**Usage:**<br>
`substring` will be a substring of `inputString` that starts at the position indiacted by `prevPostion` an has a length of `currPosition - prevPostion`.

```
substring = SUBSTR( inputString, prevPostion, (currPosition - prevPostion))
```