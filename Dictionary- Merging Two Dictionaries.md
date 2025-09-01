## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}

dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

dict3 = {*dict1,*dict2}

print(dict3)


## Output
![WhatsApp Image 2025-09-01 at 15 52 15_9a0bfaab](https://github.com/user-attachments/assets/e206fdaf-49d7-491d-aac6-b8a9fa06d81f)


## Result
Thus, a Python program that merges **two dictionaries** and combines their key-value pairs is verified.
