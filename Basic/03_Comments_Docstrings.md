# **Comments in Python & Docstrings**

## **1️⃣ What are Comments in Python?**
Comments are lines in Python code that are **ignored by the interpreter** and used to add explanations or notes for better understanding.

### **📝 How to Write a Comment?**
In Python, comments start with a `#` symbol:

```python
# This is a single-line comment in Python
print("Hello, World!")  # This is an inline comment
```

### **🛠 Purpose of Comments**
✅ Explain code for better readability
✅ Temporarily disable parts of the code
✅ Provide instructions or context

---

## **2️⃣ What are Docstrings in Python?**
Docstrings (Documentation Strings) are **multi-line string literals** used to **document a module, function, class, or method**. Unlike comments, docstrings can be accessed at runtime.

### **📌 How to Write a Docstring?**
Docstrings are enclosed in `""" triple double quotes """` or `''' triple single quotes '''`:

```python
def greet():
    """This function prints a greeting message."""
    print("Hello, Python!")
```

### **🔍 Accessing Docstrings**
Docstrings are stored in the `__doc__` attribute:

```python
print(greet.__doc__)
```

📌 **Output:**
```
This function prints a greeting message.
```

---

## **3️⃣ Difference Between Comments & Docstrings**
| Feature        | Comments | Docstrings |
|--------------|----------|------------|
| Syntax | Starts with `#` | Uses `"""` or `'''` |
| Purpose | Explain code | Document functions, classes, modules |
| Scope | Ignored by Python | Stored as `__doc__` and accessible |
| Multi-line? | ❌ No | ✅ Yes |
| Access at Runtime? | ❌ No | ✅ Yes |

---

## **✅ Best Practices**
- Use comments for **short explanations** of complex logic.
- Use docstrings to **document functions, classes, and modules**.
- Keep comments **concise and meaningful**.

---

🔥 Now you understand **comments vs. docstrings** in Python! Happy coding! 🚀
