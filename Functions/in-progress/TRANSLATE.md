# Function Name: TRANSLATE

### Usage:
Replace character occruences in a text string with a new character.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
TRANSLATE( String EXPR, String OLD, String NEW )
```
**Usage:** Returns the text string operand `EXPR` with all occurrences of each character in `OLD` replaced by its corresponding character in `NEW`. Characters in `EXPR` that are not in `OLD` are not replaced. The argument `OLD` can contain more characters than `NEW`. In this case, the extra characters at the end of `OLD` have no corresponding characters in `NEW`. If these extra characters appear in `EXPR`, they are removed from the return value.
<br>
**Optional Parameters:**<br>
**Return Type:** `Text`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
```

```