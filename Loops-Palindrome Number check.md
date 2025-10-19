## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev = (10 * rev) + temp % 10
    temp=temp//10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```
## Output
<img width="1260" height="275" alt="image" src="https://github.com/user-attachments/assets/f7215b26-43de-464a-9987-042bdc47dfc4" />


## Result
Thus, the Python program that checks whether a given number is a palindrome using loops has been successfully created and executed.
