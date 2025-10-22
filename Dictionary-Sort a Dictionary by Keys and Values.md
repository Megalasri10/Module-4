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
```
my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}
print("Original Dictionary:", my_dict)
sorted_by_keys = dict(sorted(my_dict.items()))
print("Dictionary Sorted by Keys:", sorted_by_keys)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Dictionary Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="1687" height="530" alt="image" src="https://github.com/user-attachments/assets/20c64e08-9e7c-4283-b697-9c99a79fedc8" />

## Result
The code executed successfully.
