# 🚀 Setting Up a Virtual Environment in Python

A virtual environment helps manage dependencies for different Python projects separately. Below are two methods to create and activate a virtual environment: **using `venv` (recommended)** and **using `virtualenv`**.

---

## 📌 Method 1: Using `venv` (Recommended ✅)
`venv` is built into Python 3, making it the best choice for creating virtual environments without additional installations.

### **Step 1: Create a Virtual Environment**
```sh
py -m venv myworld
```
🔹 This creates a virtual environment named `myworld` in your current directory.

### **Step 2: Activate the Virtual Environment**

#### **For Windows (Command Prompt):**
```sh
myworld\Scripts\activate
```
#### **For Windows (PowerShell):**
```sh
myworld\Scripts\Activate.ps1
```
#### **For macOS/Linux:**
```sh
source myworld/bin/activate
```

### **Step 3: Verify the Virtual Environment**
```sh
python --version
pip list
```
💡 If activated successfully, you'll see `(myworld)` before your terminal prompt.

### **Step 4: Deactivate the Virtual Environment**
```sh
deactivate
```
---

## 📌 Method 2: Using `virtualenv`
If you prefer `virtualenv`, follow these steps:

### **Step 1: Install `virtualenv` (Only Needed Once)**
```sh
pip install virtualenv
```

### **Step 2: Create a Virtual Environment**
```sh
virtualenv env
```
🔹 This creates an environment named `env` in your current directory.

### **Step 3: Activate the Virtual Environment**

#### **For Windows (Command Prompt):**
```sh
env\Scripts\activate
```
#### **For Windows (PowerShell):**
```sh
env\Scripts\Activate.ps1
```
#### **For macOS/Linux:**
```sh
source env/bin/activate
```

### **Step 4: Verify the Virtual Environment**
```sh
python --version
pip list
```

### **Step 5: Deactivate the Virtual Environment**
```sh
deactivate
```

---

## 🎯 Which Method is Best?
✅ **Use `venv`** if you're working with Python 3 (Recommended).

✅ **Use `virtualenv`** if you're working with an older Python version (Python <3.3) or need advanced features.

Happy Coding! 🚀🎉

