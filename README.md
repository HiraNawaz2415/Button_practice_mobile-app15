# 🔘 Button Practice Android App

This is a basic Android app created for practicing the use of **buttons** in Java. The app includes examples of different button types and click event handling.

---

## Features

- Basic **Button** click functionality
- Shows Toast message on click
- Demonstrates use of `setOnClickListener`
- Clean and beginner-friendly UI
- Written in Java with XML layouts

---

## What is a Button in Android?

A **Button** is a UI element that users can tap to perform an action. Buttons are defined in XML layout files and handled in Java using `setOnClickListener`.

Example:
```java
Button myButton = findViewById(R.id.myButton);
myButton.setOnClickListener(v -> {
    // Your code here
});
