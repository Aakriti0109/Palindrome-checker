# Palindrome Checker in Java

## 📌 Overview

This is a simple Java program that:

* Takes a string as input from the user
* Reverses the string
* Checks whether the string is a palindrome

A **palindrome** is a word, phrase, or sequence that reads the same forward and backward (e.g., *madam*, *racecar*).

---

## ⚙️ How the Program Works

1. The user enters a string.
2. The program reverses the string using a loop.
3. It compares the original string with the reversed string.
4. If both are the same → it is a palindrome.
   Otherwise → it is not a palindrome.

---

## ▶️ How to Run

1. Save the file as:

   ```
   PalindromeCheck.java
   ```

2. Compile the program:

   ```
   javac PalindromeCheck.java
   ```

3. Run the program:

   ```
   java PalindromeCheck
   ```

---

## 💡 Example

**Input:**

```
madam
```

**Output:**

```
Reversed string: madam
The string is a palindrome.
```

---

## 🧠 Key Concepts Used

* Java `Scanner` for user input
* `for` loop for string reversal
* `String` methods like `length()` and `charAt()`
* `equals()` for string comparison

---

## 🚀 Possible Improvements

* Ignore case sensitivity (e.g., "Madam")
* Ignore spaces and special characters
* Use `StringBuilder` for better performance

---

## 📚 License

This project is free to use for learning and educational purposes.
