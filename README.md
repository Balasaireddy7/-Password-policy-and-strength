# -Password-policy-and-strength

Below is the password policy and strength

Write a program that should return strength and a boolean value of whether the password is accepted or not.

Passwords with strength high/strong are only accepted. 

Policy:
1. Password should be between 8 to 14 characters.
2. Should use of both upper-case and lower-case letters.
3. Should contain one or more numerical digits
4. Should contain special characters, such as @, #, $ …
5. Password should not contain these words (“password”, “12345”," qwerty", "admin", ‘’username’’)
 
Strength:
1. Strong: contains min 2 characters each (upper-case, lower-case, numerical digits, special character)
2. High: contains min 1 character each and at least 2 characters of either one of (upper-case, lower-case, numerical digits, special character)
3. Moderate: contains min 1 character each of (upper-case, lower-case, numerical digits, special character)
4. Weak:  Does not contain min 1 character each (upper-case, lower-case, numerical digits, special character). Also if it does not comply with policy 1 and policy 5
