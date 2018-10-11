# Function Name: LEAST

### Usage:
Compare two types if variables to determine which one is the least in terms of value, date, or alphabetic order.
<br><br>

### Compatible Module(s):
All
<br><br>

### Signature(s):
```
LEAST( Date EXPR1, Date EXPR2, Date EXPR... )
```
**Usage:** Compares the operands and returns the earliest date.<br>
**Optional Parameters:** `Date EXPR2, Date EXPR...`<br>
**Return Type:** `Date`<br>
**Required Context:**<br>
<br>

```
LEAST( Number EXPR1, Number EXPR2, Number EXPR... )
```
**Usage:** Compares all the operands and returns the smallest value.<br>
**Optional Parameters:** `Number EXPR2, Number EXPR...`<br>
**Return Type:** `Number`<br>
**Required Context**:<br>
<br>

```
LEAST( String EXPR1, String EXPR2, String EXPR... )
```
**Usage:** Compares the values of all the text string operands. Returns the first string in alphabetic order from among its operands.<br>
**Optional Parameters:** `String EXPR2, String EXPR...`<br>
**Return Type:** `String`<br>
**Required Context:**<br>
<br>

### Code Example(s):
**Usage:**<br>
In the example below, `LEAST(80, hoursWorked)` is being used to compare the value of `hoursWorked` against `80`. The least of the two values will be used in the following expressions where `hoursAllowed` is subtracted and the result is saved to `extraHours`. 

```
 If hoursWorked > hoursAllowed Then
   (
      extraHours = LEAST(80, hoursWorked) - hoursAllowed
      awardAmount = extraHours * (rate/(2*80))
   ) 
```