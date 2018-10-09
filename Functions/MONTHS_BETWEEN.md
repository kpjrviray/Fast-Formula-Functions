# Function Name: MONTHS_BETWEEN

### Usage:
Returns the number of months between two dates.
<br><br>

### Compatible Module(s):

<br><br>

### Signature(s):

```
MONTHS_BETWEEN( date DATE1, date DATE2 )
```
**Usage:** Returns the number of months between DATE1 and DAET2. If DATE1 is later than DATE2, the result is a positive number. If DATE1
is earlier than DATE2, the result is a negative number. The return value has a numeric data type that can contain a fraction if
the dates do not differ by a whole number of months.<br>
**Optional Parameters:**<br>
**Return Type:** Date<br>
**Required Context:**<br>
<br>


### Code Example(s):
**Usage:**<br>
The example below returns the number of days between `1995/06/27` and `1995/09/27`. The return value is `3`.

```
DAYS_BETWEEN('1995/06/27 00:00:00' (date), '1995/09/27 00:00:00' (date))
```