# Function Name: ROUND

### Usage:
Rounds a value or a date to a specified date format.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
ROUND( Number NUMBER, Number PLACES )
```
**Usage:** Round `NUMBER` after a certain number of decimal `PLACES`. Rounding follows common conventions.<br>
**Optional Parameters:** `Number PLACES`<br>
**Return Type:** Number<br>
**Required Context:**<br>
<br>

// verify if below is supported
```
ROUND( Date DATE, String FMT )
```
**Usage:** Returns the result of rounding `DATE` according to string `FMT`. The default format is DDD, which represents the nearest day.
<br>
**Optional Parameters:** `String FMT`<br>
**Return Type:** `Date`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `round(rate, 2)` is used to round `rate` to `2` decimal places.
```
rate = round(rate, 2)
```