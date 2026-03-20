# 🚀 Smart Notify System

A Java-based console application that simulates a real-world notification system using core Object-Oriented Design Principles and multiple design patterns.

---

## 📌 Overview

In modern applications like banking systems, e-commerce platforms, and messaging apps, notifications play a crucial role in user engagement.
This project demonstrates a flexible and scalable notification system that supports multiple notification types and dynamic message enhancements.

---

## ✨ Features

* 📧 Supports multiple notification types:

  * Email
  * SMS
  * Push Notifications

* ⚙️ Flexible sending strategies:

  * Immediate sending
  * Delayed sending

* 🧩 Dynamic message enhancements:

  * Encryption
  * Timestamp
  * Priority tagging (custom feature)

* 📊 Observer-based system:

  * Logging system
  * Analytics tracking

* 🔒 Centralized notification management using Singleton

---

## 🧠 Design Patterns Used

| Pattern           | Purpose                                         |
| ----------------- | ----------------------------------------------- |
| Factory Pattern   | Creates notification objects (Email, SMS, Push) |
| Strategy Pattern  | Defines how notifications are sent              |
| Singleton Pattern | Ensures one global Notification Manager         |
| Observer Pattern  | Notifies logging and analytics systems          |
| Decorator Pattern | Enhances messages dynamically                   |

---

## 🛠️ Tech Stack

* Java (JDK 11/17)
* IntelliJ IDEA
* Object-Oriented Programming (OOP)

---

## 📂 Project Structure

```
src/
├── model/
├── decorator/
├── strategy/
├── notification/
├── factory/
├── singleton/
├── observer/
└── NotificationSystemApp.java
```

---

## ▶️ How to Run

1. Clone the repository
2. Open in IntelliJ IDEA
3. Run `NotificationSystemApp.java`

---

## 🧪 Sample Output

```
[System] Email notification initialized
[Immediate Strategy] Dispatching: [Encrypted] [HIGH PRIORITY] Your order has been successfully placed! @ 2026-03-20T...
[Logger] Sent: ...
[Analytics] Tracked: ...
```

---

## 🚀 Future Enhancements

* Add multithreading for asynchronous notifications
* Integrate with REST APIs (Spring Boot)
* Add database support for storing logs
* Implement retry and failure handling mechanisms

---

## 👩‍💻 Author

Tejashwini

---

## ⭐ Acknowledgment

This project is inspired by real-world notification systems and built to practice design patterns and clean architecture in Java.

---
