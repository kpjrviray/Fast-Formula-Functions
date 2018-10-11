# Function Name: DAYS_BETWEEN

### Usage:
Returns the number of days between two dates.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
DAYS_BETWEEN( Date DATE1, Date DATE2 )
```
**Usage:** Returns the number of days between `DATE1` and `DATE2`. If `DATE1` is later than `DATE2` then the result is a positive number. If `DATE1` is earlier than `DATE2` then the result is a negative number<br>
**Optional Parameters:**<br>
**Return Type:** `Date`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
The example below returns the number of days between `1995/06/27` and `1995/07/03`. Since the first argument is a later date, the return value is `-5`.
```
DAYS_BETWEEN('1995/06/27 00:00:00' (date), '1995/07/03 00:00:00' (date))
```