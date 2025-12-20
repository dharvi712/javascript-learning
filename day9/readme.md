Perfect 👍
Here is a **clean, beginner-friendly `README.md`** for **today’s JavaScript learning**, written in **simple language** and **GitHub-ready**.
You can directly **copy–paste** this into your repo.

---

# 📘 JavaScript Learning – Day 1

### Topic: `map()`, `filter()`, Objects & DOM Basics

---

## 📌 Overview

Today, I learned how to work with **arrays of objects** in JavaScript and how to process data using **modern array methods** like `filter()` and `map()`. I also learned the difference between **console output** and **displaying data on a webpage using DOM manipulation**.

This learning is implemented using a small real-world example of **student CGPA management**.

---

## 🧠 Concepts Learned

### ✅ 1. JavaScript Objects

* Stored real-world data (student name and CGPA) using objects.
* Multiple objects stored inside an array.

Example:

```js
{ name: "dharvi", cgpa: 9.3 }
```

---

### ✅ 2. `filter()` Method

* Used to **select elements** from an array based on a condition.
* Returns a **new array**.
* Does **not modify** the original array.

Example use case:

* Selecting students with CGPA ≥ 9.

---

### ✅ 3. `map()` Method

* Used to **transform data** in an array.
* Returns a **new array**.
* Can return numbers, strings, or even new objects.

Example use case:

* Increasing every student’s CGPA by `0.1`
* Creating a new array with updated CGPA values.

---

### ✅ 4. `filter()` + `map()` Chaining

* First filter the required data.
* Then transform it using map.
* Makes the code **clean and readable**.

---

### ✅ 5. Console vs DOM Output

| Method            | Purpose                    |
| ----------------- | -------------------------- |
| `console.log()`   | Debugging (developer view) |
| `alert()`         | Popup messages             |
| DOM (`innerHTML`) | Display data on webpage    |

Learned that `console.log()` **does not display anything on the webpage**.

---

### ✅ 6. DOM Manipulation (Basics)

* Used `document.getElementById()`
* Created HTML elements dynamically
* Displayed filtered results on the webpage

---

## 🛠️ Mini Project: Student Result Dashboard

### 🔹 Description

A simple dashboard that:

* Stores student data using objects
* Filters students based on CGPA
* Updates CGPA values using map
* Displays results dynamically on the webpage

---

### 🔹 Sample Data Used

```js
let students = [
  { name: "dharvi", cgpa: 9.3 },
  { name: "ananya", cgpa: 9.0 },
  { name: "vaibhavi", cgpa: 8.9 }
];
```

---

### 🔹 Features Implemented

* Display students with CGPA ≥ 9
* Increase CGPA of all students by 0.1
* Show results on the webpage using DOM

---

## 🎯 Learning Outcome

By the end of today’s learning, I am able to:

* Work with arrays of objects
* Use `filter()` and `map()` confidently
* Understand immutability in JavaScript
* Display dynamic data on a webpage
* Write clean, readable, and interview-ready JavaScript code

---

