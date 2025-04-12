# RonCAD

**RonCAD** is an Android app for architectural and engineering design. It enables users to draw simple shapes (rectangles, circles, and lines), view a sample design image, enter designer details, select design categories, and save/load their designs.

---

## Features

- Draw rectangles, circles, and lines
- Save and load designs using internal storage (JSON)
- Display architectural sample image
- Input designer name and company
- Choose from design categories (Residential, Commercial, etc.)

---

## Tech Stack

- **Kotlin**
- **Jetpack Compose**
- **kotlinx.serialization**
- **Android SDK**

---

## Project Structure

```
com/
└── roncad/
    ├── MainActivity.kt
    ├── model/
    │   ├── Shape.kt
    │   └── ShapeType.kt
    ├── ui/
    │   ├── DrawingScreen.kt
    │   ├── ShapeCanvas.kt
    │   ├── ImageDisplay.kt
    │   ├── DesignerInfo.kt
    │   └── CategorySelector.kt
    └── util/
        └── FileUtils.kt
```

---

## Getting Started

1. Clone or download the project
2. Open in Android Studio
3. Run the app on an emulator or Android device

---

## License

MIT License

---

## Author

Designed and developed by [You].

---

*This project was generated with help from ChatGPT.*