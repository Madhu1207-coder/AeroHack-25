
# 🧠 Rubik’s Cube Solver – AeroHack 2025  
**Java GUI Application | Developed for Collins Aerospace Hackathon**

---

## 🚀 Project Overview

This project was developed as part of **AeroHack 2025** organized by **Collins Aerospace**.  
It addresses the challenge:

> _"Participants are challenged to design and implement an algorithm that can solve a standard 3x3 Rubik’s Cube from any scrambled state. The solution must mimic the real-world logic of solving a cube through a sequence of valid moves."_

This Java-based application offers an intuitive Swing-based interface that allows users to input a Rubik’s Cube configuration—either through standard scramble notation or manual color selection—and visualize a solution using a beginner-friendly layer-by-layer method.

---

## 🎯 Key Features

### 🧩 Two Modes of Cube Input
- **Text Scramble Mode:**
  - Input scramble using standard cube notation (e.g., `R U R' U'`).
  - Apply your scramble or generate a random one.
  - View animated solution steps.
  
- **Color Input Mode:**
  - Manually assign colors to all 6 faces of the cube.
  - Use a palette and face selector to enter real-world cube data.
  - Reset input or proceed to solution visualization.

### 🎞️ Animation Controls
- Start, pause, rewind, and fast-forward solving animation.
- Adjust animation speed with a slider.
- **Move display**:
  - 🔴 Red: moves already completed  
  - ⚫ Black: upcoming moves

---

## 🛠️ Technologies Used

| Tool / Language | Purpose                     |
|-----------------|-----------------------------|
| Java (JDK 1.8+) | Core application logic       |
| Swing           | GUI Interface                |
| Beginner’s Method | Cube solving algorithm     |

---

## 📁 Folder Structure

```

Madhumitha Rubiks Cube Solver/
├── doc/                                # Auto-generated Javadoc documentation
│   ├── class-use/
│   ├── index-files/
│   ├── Cube.html
│   ├── CubeDisplayer.html
│   ├── CubePainter.html
│   ├── Cubie.html
│   ├── CubeColor.html
│   ├── Debugging.html
│   ├── SolutionFinder.html
│   ├── allclasses-frame.html
│   ├── allclasses-noframe.html
│   ├── constant-values.html
│   ├── deprecated-list.html
│   ├── help-doc.html
│   ├── index.html
│   ├── overview-tree.html
│   ├── package-frame.html
│   ├── package-list
│   ├── package-summary.html
│   ├── package-tree.html
│   ├── package-use.html
│   ├── script.js
│   ├── serialized-form.html
│   └── stylesheet.css
│
├── images/                             # (Optional) Screenshots and UI assets
│   └── (Place GUI preview images here)
│
├── src/                                # Java source files and compiled class files
│   ├── resources/
│   ├── Cube.java
│   ├── Cube.class
│   ├── CubeDisplayer.java
│   ├── CubeDisplayer.class
│   ├── CubeDisplayer$1.class
│   ├── CubePainter.java
│   ├── CubePainter.class
│   ├── CubePainter$1.class
│   ├── Cubie.java
│   ├── Cubie.class
│   ├── CubeColor.java
│   ├── CubeColor.class
│   ├── Debugging.java
│   ├── SolutionFinder.java
│   └── package-info.java
│
└── README.md                           # Project documentation file


````

---

## 📥 Installation & Usage

### 🔧 Prerequisites
- Java JDK 1.8 or above

### 🖥️ Run the Application
```bash
git clone https://github.com/Madhu1207-coder/AeroHack-25.git
cd AeroHack-25/src
javac CubeDisplayer.java
java CubeDisplayer
````

---

## 📚 Notation Reference

Before using scramble input, learn the **standard Rubik’s Cube notation**:

| Notation | Meaning                   |
| -------- | ------------------------- |
| `U`      | Up face clockwise         |
| `U'`     | Up face counter-clockwise |
| `R`, `L` | Right / Left face         |
| `F`, `B` | Front / Back face         |
| `D`      | Down face                 |

---

## 👨‍🏫 Educational Objective

This tool aims to help **beginners learn how to solve a cube** by:

* Breaking down steps using a real-world approach.
* Visually demonstrating solving logic.
* Supporting interactive learning through manual configuration.

---

# 📷 Screenshot Gallery

This section showcases the core input and output screenshots of the AeroHack-25 solution. These examples help visualize the working of the model for both **color** and **text** processing.

| Type                   | Screenshot |
|------------------------|------------|
| 🎨 Color Input (Sample 1)  | ![Color Input](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/color%20input.jpeg) |
| 🎨 Color Input (Sample 2)  | ![ColorInput](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/ColorInput.jpeg) |
| 🎨 Color Output (Solution 1) | ![Color Solution](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/Color%20Solution.jpeg) |
| 🎨 Color Output (Solution 2) | ![ColorSolution](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/ColorSolution.jpeg) |
| 📝 Text Input              | ![Text Input](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/Text.jpeg) |
| 📝 Text Output             | ![Text Output](https://github.com/Madhu1207-coder/AeroHack-25/blob/main/code/images/text%201.jpeg) |





## 🙋‍♀️ Developed By

**Madhumitha B**
📧 [Madhumithab1207@gmail.com](mailto:Madhumithab1207@gmail.com)
📱 9344867424
🎓 B.Tech AI & DS, Velammal Engineering College
🔗 [LinkedIn](https://www.linkedin.com/in/madhumitha-b-a545a525b)



```

