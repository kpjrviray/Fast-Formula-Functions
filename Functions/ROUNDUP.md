# Function Name: ROUNDUP

### Usage:
Round a number to the next highest whole number or a certain number of decimal places.
<br><br>

### Compatible Module(s):
ALL
<br><br>

### Signature(s):
```
ROUNDUP( Number M, Number N ) or ROUND_UP(Number M, Number N)
```
**Usage:** Rounds `M` up to `N` decimal places. The default number of places is 0.<br>
**Optional Parameters:** `Number N`<br>
**Return Type:** `Number`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
The example below returns `2.35`. Note the `.3401` that has been rounded to `.35`.
```
ROUND_UP(2.3401, 2)
```
<br>

**Usage:**<br>
The example below returns `2.34`. Note that the `.3400` was not rounded because of the trailing zero's.
```
ROUND_UP(2.3400, 2)
```