# Function Name: TRUNC

### Usage:
Truncates a value to or a date to a specified date format. 
<br><br>

### Compatible Module(s):

<br><br>

### Signature(s):

```
TRUNC( Number N, Number PLACES ) OR TRUNCATE( Number N, Number PLACES )
```
**Usage:**Truncates `N` down to `PLACES` decimal places. The default number of places is 0.<br>
**Optional Parameters:**<br>
**Return Type:** `Number`<br>
**Required Context:**<br>
<br>

```
TRUNC( Date DATE, String FMT )
```
**Usage:** Returns the result of truncating `DATE` according to `FMT`. The default format is DDD, which represents a whole day.<br>
**Optional Parameters:**<br>
**Return Type:** `Date`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
Truncates `2.3401` down to two decimales and returns the valuie `2.34`.
```
TRUNC(2.3401, 2)
```