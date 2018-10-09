# Function Name: TRUNC

#### Usage:
Truncates a value to or a date to a specified date format. 
<br><br>

#### Compatible Modules:

<br><br>

#### Signature(s):

```
TRUNC( Num N, Num PLACES ) OR TRUNCATE( Num N, Num PLACES )
```
**Usage:**Truncates N down to PLACES decimal places. The default number of places is 0.<br>
**Optional Parameters:**<br>
**Return Type:** Num<br>
**Required Context:**<br>
<br>

```
TRUNC( date DATE, string FMT )
```
**Usage:** Returns the result of truncating DATE according to FMT. The default format is DDD, which represents a whole day.<br>
**Optional Parameters:**<br>
**Return Type:** Date<br>
**Required Context:**<br>
<br>

#### Code Example(s):
**Usage:**<br>
Truncates `2.3401` down to two deciamles and returns the valuie `2.34`.
```
TRUNC(2.3401, 2)
```