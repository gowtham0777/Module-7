# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
```
def sum(n):
    n=abs(n)
    if n==0:
        return 0
    else:
        return n%10 +sum(n//10)
n=int(input())
print(sum(n))
```

## OUTPUT
<img width="1045" height="305" alt="image" src="https://github.com/user-attachments/assets/8575ddf3-95d9-45c7-8000-bb5fe3599c6c" />

## RESULT
Thus, the program has been successfully executed.
