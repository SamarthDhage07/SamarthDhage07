## Hi there 👋
# 🔢 Check Even or Odd Using Bit Manipulation
# 🔢 Check Even or Odd Using Bit Manipulation

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=openjdk">
  <img src="https://img.shields.io/badge/Topic-Bit%20Manipulation-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Difficulty-Beginner-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Time%20Complexity-O(1)-red?style=for-the-badge">
</p>

<p align="center">
  <b>A simple Java program to determine whether a number is Even or Odd using Bitwise Operators instead of the modulus (%) operator.</b>
</p>

---

## 📖 About

This project demonstrates one of the most fundamental applications of **Bit Manipulation**.

Instead of using:

```java
n % 2 == 0
```

the program uses the **Bitwise AND (`&`)** operator:

```java
(n & 1) == 0
```

This technique is commonly used in competitive programming, interviews, and low-level programming because it executes in **constant time**.

---

## 🚀 How It Works

Every integer has a binary representation.

| Number | Binary | Last Bit | Result |
|---------|---------|----------|--------|
| 8 | 1000 | 0 | ✅ Even |
| 13 | 1101 | 1 | ✅ Odd |
| 24 | 11000 | 0 | ✅ Even |
| 31 | 11111 | 1 | ✅ Odd |

The last bit (Least Significant Bit) tells us whether a number is even or odd.

```java
if ((n & 1) == 0)
```

- `0` → Even Number
- `1` → Odd Number

---

## 💻 Sample Output

### Input

```java
n = 8
```

### Output

```
even number
```

---

## ⚡ Algorithm

```
Start

Input Number

Perform:
number & 1

If result == 0
      Print "Even Number"
Else
      Print "Odd Number"

End
```

---

## 📂 Project Structure

```
📦 Check-Even-Odd
 ┣ 📜 _01_check_Even_Odd.java
 ┗ 📄 README.md
```

---

## ⏱ Complexity Analysis

| Operation | Complexity |
|-----------|------------|
| Time | **O(1)** |
| Space | **O(1)** |

---

## 🎯 Concepts Covered

- ✅ Bit Manipulation
- ✅ Bitwise AND (`&`)
- ✅ Binary Numbers
- ✅ Java Methods
- ✅ Conditional Statements
- ✅ Efficient Number Checking

---

## 🌟 Why Bit Manipulation?

✔ Faster than traditional arithmetic operations in many low-level implementations.

✔ Frequently asked in coding interviews.

✔ Foundation for advanced DSA and Competitive Programming.

---

## 🛠 Built With

<p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
</p>

---

## 👨‍💻 Author

### **Samarth Dhage**

### 🌐 Connect with Me

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sam__dhage)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samarth-dhage-72a934382/)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhagesamarth2027@gmail.com)

---

## ⭐ Support

If you found this repository helpful,

🌟 **Star this repository** and follow me for more **DSA, Java, and Competitive Programming** solutions!

<p align="center">

### 🚀 Happy Coding! 💙

</p>
</p>
