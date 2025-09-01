# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list a with some integer elements.
2. Use a *try-except* block:
   - In the try block, attempt to access an index that is out of range (e.g., list1[6]).
   - In the except block, catch the error and print a custom message "6 is not accepted".
3. Print the result based on whether the index access succeeds or fails.


## 🧾 Program
try:

    n=int(input())
    
    a = []
    
    for i in range(1,n+1):
    
        n1=int(input())
        
        a.append(n1)
        
    print(a)
    
    print(a[6])
                
                
except IndexError:
        print("6 is not accepted")

## Output
![WhatsApp Image 2025-09-01 at 16 03 26_4a190ce2](https://github.com/user-attachments/assets/477fafa3-4e77-437d-95b1-5437f25032f3)


## Result
Thus,a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is verified.
