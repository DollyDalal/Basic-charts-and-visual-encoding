# 📊 BASIC CHARTS & VISUAL ENCODING IN PYTHON 🎨

---

## 🚀 INTRODUCTION

Data visualization is the process of **representing data using charts and graphs**.

👉 It helps in:

* 👀 Understanding data easily
* 📊 Identifying patterns & trends
* 📈 Making better decisions

---

## 🔹 1. BASIC CHARTS 📉

---

### 1️⃣ Bar Chart 📊

### 💡 What is it?

Used to compare values between categories

```python
import matplotlib.pyplot as plt

x = ["A", "B", "C"]
y = [10, 20, 15]

plt.bar(x, y)
plt.show()
```

---

### 2️⃣ Line Chart 📈

### 💡 What is it?

Used to show trends over time

```python
plt.plot(x, y)
plt.show()
```

---

### 3️⃣ Pie Chart 🥧

### 💡 What is it?

Shows percentage distribution

```python
plt.pie(y, labels=x, autopct="%1.1f%%")
plt.show()
```

---

### 4️⃣ Histogram 📊

### 💡 What is it?

Shows distribution of numerical data

```python
data = [10, 20, 20, 30, 40]

plt.hist(data)
plt.show()
```

---

### 5️⃣ Scatter Plot 🔵

### 💡 What is it?

Shows relationship between two variables

```python
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.scatter(x, y)
plt.show()
```

---

## 🔹 2. VISUAL ENCODING 🎨

### 💡 What is it?

Visual encoding means **representing data using visual elements** like position, color, size, and shape.

---

### 🔧 TYPES OF VISUAL ENCODING

---

### 1️⃣ Position 📍

👉 Placement on X and Y axis

---

### 2️⃣ Color 🎨

👉 Colors represent categories

```python
plt.bar(x, y, color=["red", "blue", "green"])
plt.show()
```

---

### 3️⃣ Size 🔵

👉 Size shows importance

```python
plt.scatter(x, y, s=[50, 100, 200, 300])
plt.show()
```

---

### 4️⃣ Shape 🔷

👉 Different shapes for categories

```python
plt.scatter(x, y, marker="o")
plt.show()
```

---

### 5️⃣ Labels & Text 🏷️

👉 Adds clarity

```python
plt.title("Sample Chart")
plt.xlabel("X Axis")
plt.ylabel("Y Axis")
plt.show()
```

---

## 🔹 3. MATPLOTLIB THEORY 📊

### 💡 What is Matplotlib?

**Matplotlib** is a Python library used for **creating basic static charts and graphs**.

---

### 🤔 Why use Matplotlib?

* 📈 Simple and easy to use
* 🎯 Full control over plots
* 📊 Supports many chart types

---

### 🔥 Features

* Line, bar, pie, histogram, scatter plots
* Custom labels, colors, and styles
* Works well with pandas

---

### 📌 Example

```python
import matplotlib.pyplot as plt

plt.plot([1,2,3],[4,5,6])
plt.show()
```

---

## 🔹 4. SEABORN THEORY 🎨

### 💡 What is Seaborn?

**Seaborn** is an advanced visualization library built on top of matplotlib.

👉 It is used for **beautiful and statistical graphs**.

---

### 🤔 Why use Seaborn?

* 🎨 Better design and styling
* 📊 Built-in statistical plots
* 🤖 Works directly with DataFrames

---

### 🔥 Features

* Heatmaps 🔥
* Pair plots 🔗
* Distribution plots 📊
* Box plots 📦

---

### 📌 Example

```python
import seaborn as sns
import matplotlib.pyplot as plt

data = [10, 20, 30, 40]
sns.histplot(data)
plt.show()
```

---

## 🔥 DIFFERENCE BETWEEN MATPLOTLIB & SEABORN

| Feature | Matplotlib 📊    | Seaborn 🎨                |
| ------- | ---------------- | ------------------------- |
| Level   | Basic            | Advanced                  |
| Style   | Simple           | Attractive                |
| Use     | General plotting | Statistical visualization |

---

## 🧰 LIBRARIES USED

* 📊 matplotlib
* 🐼 pandas
* 🎨 seaborn

---

## ✅ CONCLUSION

✔ Matplotlib is used for basic plotting
✔ Seaborn is used for advanced and stylish visuals
✔ Both help in better data understanding.
