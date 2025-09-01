# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
from collections import OrderedDict

d={'ravi':'10','rajnish':'9','sanjeev':'15','yash':'2','suraj':'32'}

d1=OrderedDict(sorted(d.items()))

print(d1)

## Sample Output

![WhatsApp Image 2025-09-01 at 14 52 20_5dfdf539](https://github.com/user-attachments/assets/2571423e-9f24-4eae-a313-9894c1506b35)

## Result
Thus,a Python program that sorts a dictionary's is verified.

