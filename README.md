# 🏙️ Islamabad City Checker

This simple JavaScript assignment checks whether the city **"Islamabad"** exists in a predefined array of Pakistani cities. If found, it alerts the user with a message highlighting Islamabad as the cleanest city.

---

## 📌 About

The goal of this project is to practice JavaScript array handling and conditional logic by:

- Creating an array of city names (e.g., Karachi, Lahore, Islamabad, etc.)
- Searching the array for the city `"Islamabad"`
- Displaying a specific message using `alert()` if Islamabad is found

---

## 🎯 Objective

> If **"Islamabad"** exists in the array, the program will show:  
> `"Islamabad is the cleanest city of Pakistan!"`

---

## 🧠 Key Concepts Practiced

- Arrays in JavaScript
- Using `includes()` or `indexOf()` to search elements
- Conditional statements (`if`)
- Alert box for user interaction

---

## 🛠 Technologies Used

- 🧱 HTML (basic page structure)
- ⚙️ JavaScript (array logic and alert)

---

## 💡 Sample Code Logic

```js
var cities = ["Karachi", "Lahore", "Islamabad", "Peshawar"];
if (cities.includes("Islamabad")) {
  alert("Islamabad is the cleanest city of Pakistan!");
}
