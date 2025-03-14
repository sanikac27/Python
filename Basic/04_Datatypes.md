# **Data Types & Built-in Data Types in Python**

## **1️⃣ Introduction to Data Types**
Data types define the kind of data a variable can hold in Python. Python provides **built-in data types** to handle different types of values efficiently.

### **📌 Categories of Data Types:**
1. **Mutable Data Types** → Can be changed after creation.
2. **Immutable Data Types** → Cannot be changed after creation.

---

## **2️⃣ Mutable Data Types (Can be Modified)**
Mutable data types allow modifications like adding, removing, or updating elements **without changing the memory address**.

### **🔹 List**
- A **list** is an ordered, mutable collection of elements.
- Lists can hold different data types and support various operations.

#### **✅ Creating a List:**
```python
my_list = [10, 20, 30, "Python", True]
```

#### **✅ List Operations:**
```python
my_list.append(40)   # Adds an element
my_list.remove(20)   # Removes an element
my_list[1] = 50      # Modifies an element
```

### **🔹 Set**
- A **set** is an unordered collection of unique elements.
- It does not allow duplicate values and is useful for mathematical operations.

#### **✅ Creating a Set:**
```python
my_set = {1, 2, 3, 4, 5}
```

#### **✅ Set Operations:**
```python
my_set.add(6)       # Adds an element
my_set.remove(3)    # Removes an element
```

### **🔹 Dictionary**
- A **dictionary** stores key-value pairs.
- Keys must be unique and immutable, while values can be of any type.

#### **✅ Creating a Dictionary:**
```python
my_dict = {"name": "Alice", "age": 25, "city": "New York"}
```

#### **✅ Dictionary Operations:**
```python
my_dict["age"] = 26   # Updating a value
my_dict["country"] = "USA"  # Adding a new key-value pair
```

---

## **3️⃣ Immutable Data Types (Cannot be Modified)**
Immutable data types **cannot be modified** after creation. Any operation results in a new object being created.

### **🔹 Numbers**
- Python supports **int, float, complex** number types.
- These are immutable because mathematical operations create new objects.

#### **✅ Examples:**
```python
a = 10   # Integer
b = 3.14  # Float
c = 2 + 3j  # Complex number
```

### **🔹 String**
- A **string** is a sequence of characters enclosed in quotes.
- Strings are immutable, meaning modifications create a new string.

#### **✅ Creating a String:**
```python
my_str = "Hello, Python!"
```

#### **✅ String Operations:**
```python
new_str = my_str.replace("Hello", "Hi")  # Creates a new string
```

### **🔹 Tuple**
- A **tuple** is an ordered collection of elements like a list but **immutable**.
- Elements cannot be changed after creation.

#### **✅ Creating a Tuple:**
```python
my_tuple = (1, 2, 3, "Python", True)
```

#### **✅ Tuple Operations:**
```python
tuple_length = len(my_tuple)  # Get length
value = my_tuple[1]  # Access an element
```

---

## **4️⃣ Mutable vs Immutable Data Types**
| Feature | Mutable Data Types | Immutable Data Types |
|---------|------------------|------------------|
| Modifiability | ✅ Can be changed | ❌ Cannot be changed |
| Memory Address | Remains the same | Changes when modified |
| Examples | List, Set, Dictionary | Numbers, String, Tuple |

---

## **5️⃣ Summary**
✅ **Mutable data types** → List, Set, Dictionary (Can be modified).
✅ **Immutable data types** → Numbers, String, Tuple (Cannot be modified).
✅ Choosing the right data type helps in **efficient memory usage and performance optimization**.

---

🚀 **Now you have a clear understanding of Python's data types! Happy coding!** 🎯

