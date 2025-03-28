# ✍️ Handwriting Recognition System

A Java-based neural network application that recognizes handwritten characters from a 5x6 grid. The project implements a feedforward neural network with backpropagation, complete with GUI input, training/testing modes, and real-time error visualization.

---

![Built With](https://img.shields.io/badge/Built%20With-Java-blue)
![Neural Network](https://img.shields.io/badge/AI-Feedforward%20Neural%20Net-orange)
![Status](https://img.shields.io/badge/Status-Always_Improving-yellow)

---

## 🚀 Features

- 🧠 **Feedforward Neural Network** – Learns to recognize characters through training
- ✍️ **5x6 Input Grid** – Users draw characters on a simplified grid layout
- 🔁 **Training & Testing Modes** – Switch between learning new characters or evaluating model performance
- 📉 **Real-time Error Visualization** – Watch the network improve over time
- 🖼️ **Java AWT GUI** – Intuitive interface for drawing and interaction
- 🔧 **Backpropagation Algorithm** – Trains the network by minimizing output error

---

## 🛠️ Technologies Used

| Component            | Technology       |
|----------------------|------------------|
| Language             | Java             |
| ML Logic             | Feedforward Neural Network w/ Backpropagation |
| GUI                  | Java AWT         |
| Development Platform | Any Java-capable IDE / Terminal |
| Version Control      | Git + GitHub     |

---

## 📂 Project Structure

```
Handwriting-Recognition-System/
├── Main.java            # Application entry point
├── Network.java         # Neural network logic
├── GUI.java             # User interface code
├── Util.java            # Helper functions
├── README.md            # Documentation
└── *.class              # Compiled files (after build)
```

---

## ▶️ How to Use

### 💻 Prerequisites

- Java Development Kit (JDK 8 or higher)
- NetBeans, IntelliJ, or any Java-capable IDE (or use command line)

### 📦 Step 1: Download the Project

- Clone or download the repo and open it in your IDE or extract the files if zipped.

### 🛠 Step 2: Compile the Program

**Using terminal:**
```bash
javac -d bin src/*.java
```

**Or in an IDE:** Right-click project > Build

### ▶️ Step 3: Run the Program

**Using terminal:**
```bash
java -cp bin Main
```

**Or in an IDE:** Right-click `Main.java` > Run

---

## 🧯 Troubleshooting

- **GUI doesn't open?** Ensure you're running `Main.java`, not individual files.
- **Java errors?** Confirm you're using JDK 8 or higher and files are in the correct structure.
- **Drawing not registering?** Use mouse clicks to fill squares; reset the grid to retry.

---

## 🖼️ Demo

Below is a visual demo of the Handwriting Recognition System in action:

<p align="center">
  <img src="demo images/training.png" alt="Training Mode" width="400"/>
  &nbsp;&nbsp;
  <img src="demo images/testing.png" alt="Testing Mode" width="400"/>
</p>

- **Left:** Training mode, where the neural network is learning to recognize new characters.
- **Right:** Testing mode, where the trained network predicts user-drawn characters.

## 🙌 Acknowledgments

- **Java AWT** – For the lightweight UI framework
- **Neural Network community** – For tutorials and foundational math
- **Professor T. Henry** – For project support and feedback
- **Open source inspiration** – For general architecture ideas and optimizations
