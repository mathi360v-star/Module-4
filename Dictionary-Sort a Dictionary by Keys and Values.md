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
def dictionary():     
    key_value = {}    

    key_value[2] = 56       
    key_value[1] = 2 
    key_value[5] = 12 
    key_value[4] = 24 
    key_value[6] = 18      
    key_value[3] = 323 

    print("Keys and Values sorted in ascending order by value:")

    for k, v in sorted(key_value.items(), key=lambda item: item[1]):
        print(k, ":", v)
dictionary()

```

## Sample Output

<img width="522" height="90" alt="image" src="https://github.com/user-attachments/assets/e3103511-20e8-44c1-9503-9ee02d3695c5" />


## Result
The Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order is executed successfully.


