
## Section 1 – Variables

### Question 4: Valid or Invalid?

1. `let 123name = "Ravi";`
   - Invalid – Variable name cannot start with a number.

2. `let $amount = 2000;`
   - Valid – Dollar sign ($) is allowed in variable names.

3. `let var = "keyword";`
   - Invalid – `var` is a reserved JavaScript keyword.

4. `let is-Eligible = true;`
   - Invalid – Hyphen (-) is not allowed in variable names.

5. `let homeTown = "Chennai";`
   - Valid – It follows camelCase naming convention.



### Question 5: Valid Variable Declaration

**Correct Answer: C. `let fullName = "Ravi";`**

Explanation: JavaScript variable names cannot start with numbers, cannot contain hyphens, and cannot use reserved keywords such as `var`.



### Question 6: Identify the Error

**Correct Answer: B. Value should be inside quotes.**

Explanation: `Hyderabad` is a string value, so it must be written inside quotation marks.

Correct code:
`let city = "Hyderabad";`



### Question 7: Boolean Declaration

**Correct Answer: C. `let isHosteller = true;`**

Explanation: JavaScript boolean values are written in lowercase: `true` or `false`. They should not be enclosed in quotation marks.




### Question 8: Object Declaration

**Correct Answer: B. `let student = {course: "BSc", college: "Govt"};`**

Explanation: An object stores data in key-value pairs. String values must be enclosed in quotation marks.



### Question 9: What Will This Code Do?

**Correct Answer: C. Stores two string values.**

Explanation: Both `firstName` and `lastName` contain text enclosed in quotation marks, so both variables store string values.

Code:
`let firstName = "Arjun";`
`let lastName = "Reddy";`



### Question 10: Identify the Invalid Variable Name

**Correct Answer: C. `is-Eligible`**

Explanation: A hyphen (-) is not allowed in JavaScript variable names. JavaScript treats it as a subtraction operator.

Valid alternative:
`let isEligible = true;`



### Question 11: Identify the Data Type

**Correct Answer: C. String**

Explanation: The value `"2027"` is enclosed in quotation marks, so JavaScript treats it as a string, not a number.




## Section 2 – Type Conversion

### Question 1: Predict the Output

**Statement 1:**
`"20" - "5" + 3`

Output: `18`

Explanation: The `-` operator converts both strings into numbers. Then 20 - 5 + 3 = 18.

**Statement 2:**
`4 + "6" - 2`

Output: `44`

Explanation: The `+` operator concatenates 4 and "6" to form "46". The `-` operator converts "46" into a number. So, 46 - 2 = 44.

**Statement 3:**
`"8" * 2 + "2"`

Output: `162`

Explanation: The `*` operator converts "8" into 8. Then 8 * 2 = 16. The `+` operator concatenates 16 with "2", producing "162".

**Statement 4:**
`"7" + 2 * 3`

Output: `76`

Explanation: Multiplication happens first: 2 * 3 = 6. Then `+` concatenates "7" and 6, producing "76".



### Question 2: Implicit vs Explicit Conversion

#### Part A: Create Your Own Examples

**Example 1 – String Concatenation using +**

`let result1 = "Age: " + 20;`

Output: `"Age: 20"`

Explanation: JavaScript converts the number 20 into a string and joins it with "Age: ".

**Example 2 – Numeric Conversion using -**

`let result2 = "30" - 10;`

Output: `20`

Explanation: JavaScript converts the string "30" into a number because the subtraction operator performs numeric conversion.



### Question 3: Mix Data Types

Given:
- `a = "5"` → String
- `b = 2` → Number
- `c = true` → Boolean

**Statement 1:**
`console.log(a + b + c);`

Output: `"52true"`

Explanation: First, + joins "5" and 2 to produce "52". Then it joins "true", resulting in "52true". String concatenation occurs.

**Statement 2:**
`console.log(Number(a) + b + c);`

Output: `8`

Explanation: Number(a) converts "5" into 5. Then 5 + 2 + true. JavaScript converts true into 1. Result = 8.

**Statement 3:**
`console.log(a - c);`

Output: `4`

Explanation: The - operator converts "5" into 5 and true into 1. Result = 5 - 1 = 4.

**Statement 4:**
`console.log(a * (b + c));`

Output: `15`

Explanation: First, b + c = 2 + 1 = 3. Then multiplication converts "5" into 5. Result = 5 × 3 = 15.


