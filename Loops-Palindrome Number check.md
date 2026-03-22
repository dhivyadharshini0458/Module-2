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
temp = num
count =0
while num>0:
    digit =num%10
    count= count*10+digit
    num//=10
if temp== count:
    print("The given number {} is a Palindrome".format(temp))
else:
    print("The given number {} is not a palindrome".format(temp))
```

## Output
<img width="404" height="82" alt="Screenshot 2026-03-22 083403" src="https://github.com/user-attachments/assets/5db7ad65-f0d8-4fbd-a349-11e1952b5749" />


## Result

Thus, the python program to check whether the given number is palindrome or not is executed successfully.
