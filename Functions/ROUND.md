# Function Name: ROUND

### Usage:
Rounds a value or a date to a specified date format.
<br><br>

### Compatible Modules:
All
<br><br>

### Signature(s):

```
ROUND( Number Number, Number PLACES )
```
**Usage:** Round a number (Number) after a certain number of decimal places (PLACES).<br>
**Optional Parameters:** Number PLACES<br>
**Return Type:** Number<br>
**Required Context:**<br>
<br>

// verify if below is supported
```
ROUND( date DATE, String FMT )
```
**Usage:** Returns the result of rounding DATE according to string FMT. The default format is DDD, which represents the nearest day.
<br>
**Optional Parameters:** String FMT<br>
**Return Type:** Date<br>
**Required Context:**<br>
<br>


### Code Example(s):
**Usage:**<br>
In the example below, `round(rate, 2)` is used to round `rate` to two decimal places.

```
rate = round(rate, 2)
```