# 🩸 Draw View - v0.0.2

## 🎨 Introduction
Welcome to **Draw**, a powerful and flexible drawing library! This library allows you to easily integrate drawing functionalities into your Android applications. Powered by **Draview**, it provides smooth and dynamic drawing features.

---

## 🔥 Features
✅ Lightweight & easy to use  
✅ High-performance drawing engine  
✅ Fully customizable  
✅ Supports multiple brush styles & colors  
✅ Seamless integration with Android applications  

---

## 🛠 Installation
To add **Draw v0.0.2** to your project, include the following dependency in your **build.gradle**:

```gradle
implementation("com.github.PrashantX02:Draw:v0.0.2")
```

Also, make sure you have **JitPack** and **JCenter** repositories in your **build.gradle**:

```gradle
repositories {
    maven { url = uri("https://jitpack.io") }
    jcenter()
}
```

---

## 🚀 Usage
Here’s a quick example of how to use **Draw** in your project:

```XML
 <com.pain.clibrary.DrawingView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

// Kotlin code

drawingView.brushColour(R.color.purple_500)
drawingView.brushSize(5f)
---

## 📜 License
This project is licensed under the **MIT License**. Feel free to modify and use it in your projects.

---

## 🤝 Contributing
We welcome contributions! Feel free to submit issues, fork the repository, and open pull requests.

---

💉 **Unleash your creativity with Draw!** 🖌️
