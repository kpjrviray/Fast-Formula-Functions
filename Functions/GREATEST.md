# Function Name: GREATEST

### Usage:
Compare two types if variables to determine which one is the GREATEST in terms of value, date, or alphabetic order.
<br><br>

### Compatible Modules:
All
<br><br>

### Signature(s):

```
GREATEST( date EXPR1, date EXPR2, date EXPR... )
```

**Usage:** Compares the operands and returns the latest date.<br>
**Optional Parameters:** date EXPR2<br>
**Return Type:** Date<br>
**Required Context:**<br>
<br>
```
GREATEST( Number EXPR1, Number EXPR2, Number EXPR... )
```

**Usage:** Compares all the operands and returns the largest value.<br>
**Optional Parameters:** date EXPR2<br>
**Return Type:** Number<br>
**Required Context**:<br>
<br>
```
GREATEST( String EXPR1, String EXPR2, String EXPR... )
```

**Usage:** Compares the values of all the text string operands. It returns the value of the last string in alphabetic order.<br>
**Optional Parameters:** date EXPR2<br>
**Return Type:** String<br>
**Required Context:**<br>
<br>
