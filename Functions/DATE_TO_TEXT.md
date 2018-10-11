# Function Name: DATE_TO_TEXT

### Usage:
Coverts a date variable type to a formatted string type.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
DATE_TO_TEXT( Date DATE, String FORMAT )
TO_CHAR( Date DATE, String FORMAT )
TO_TEXT( Date DATE, String FORMAT )
```
**Usage:** Converts `DAT` to a character string with format specified by `FORMAT`.<br>
**Optional Parameters:** `String FORMAT`<br>
**Return Type:** `String`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `date` is `1989-03-12 00:00:00` and will be converted to the string `1989-03-12`
```
TO_CHAR(date, 'YYYY-MM-DD')
```