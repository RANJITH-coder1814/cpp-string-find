# cpp-string-find
Beginner-friendly C++ example for understanding string search using find()
# cpp-string-find

A basic C++ program that demonstrates how to use the `find()` function in the C++ `string` class to locate a character inside a string.

---

## 📌 Program Description

This program searches for a specific character in a string and prints the index position of that character.

---

## 🧠 Concepts Used

- C++ strings
- `string::find()` function
- Input / Output using `cout`

---

## 🧾 Code Example

```cpp
#include<iostream>
using namespace std;

int main(){
    string s = "how are you";
    cout << s.find("w") << endl;
}

