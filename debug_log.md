# debug_log.md
# Author: Aigerim Valiyeva

## Bug 1
Error type: KeyError
File + line: week8-buggy.py, line 12
What the error means: Python is trying to access a dictionary key called 'amount', but the key does not exist in one of the records.
What I told the duck: The function starts with total = 0 and goes through each record. It tries to add the amount from each record to the total. I noticed that the first record has a different spelling for the key.
What I tried: I ran the code and checked the error message. Then I added a print statement inside the loop to see each record and find the problem.
How I fixed it: I changed 'amout' to 'amount' in the first record and removed the debug print.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python cannot compare an integer with a string using >.
How I fixed it: I removed the quotes aroung 1000 so Python compares two numbers insted of a number and a string.

## After Fixing Both Bugs
Final output: 
Total: $5150.00 across 3 records
True

Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes
Exact prompt I used: Can you explain what a Python KeyError means and how to identify the cause of the error using debugging techniques, without providing the corrected code?
What AI explained: AI helped me understand the error messages and how to identify mistakes in Python code.
What I changed myself: I corrected the errors in my code and tested the results.
Can I explain every fixed line? Yes

## What I learned
I learned how to red Python error messages and find where the problem is. I also learned that small mistakes like typos or using the wrong data type can stop the whole program. Using print statements helped me understand what was happening. 