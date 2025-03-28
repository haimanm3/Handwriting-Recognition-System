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

Follow these steps to run the Handwriting Recognition System using the provided `.jar` file.

---

### 💻 Prerequisites

- **Java Runtime Environment (JRE 8 or higher)**
- Optionally, a Java IDE like **NetBeans** or **Eclipse**

---

### 📦 Step 1: Download the Project

1. Go to the [GitHub repository](https://github.com/haimanm3/Handwriting-Recognition-System).
2. Click the green **Code** button, then **Download ZIP**.
3. Extract the folder on your machine.

You should see:

```
Handwriting-Recognition-System/
├── Handwriting Recognition System.jar
├── demo images/
├── neural_base/
└── README.md
```

---

### ▶️ Step 2: Run the Application

#### ✅ Option 1: Using Terminal/Command Prompt

1. Open your terminal or command prompt.
2. Navigate to the folder containing the `.jar` file.
3. Run:

```bash
java -jar Handwriting Recognition System.jar
```

---

#### ✅ Option 2: Without Terminal (Double-click)

1. Navigate to the folder containing `Handwriting Recognition System.jar`.
2. Double-click the file to run it.

> 💡 If nothing happens:
> - Ensure you have Java installed.
> - On some systems, you may need to right-click → **Open With** → **Java**.

---

#### ✅ Option 3: Using an IDE

1. Open your Java IDE (NetBeans, IntelliJ, Eclipse).
2. Create a new project and add the `.jar` as an external library or run configuration.
3. Run the project or create a custom run config pointing to the `.jar`.

---

### 🧯 Troubleshooting

- **Java not recognized?**
  - Ensure Java is installed and added to your system PATH.
- **GUI not opening?**
  - Make sure the `.jar` file is not corrupted.
  - Check that you are using Java 8+.
- **Double-click doesn't work?**
  - Try running it via terminal as described above.
 
---

## 🖼️ Demo

Below is a visual demo of the Handwriting Recognition System in action:

<p align="center">
  <img src="demo images/training.png" alt="Training Mode" width="480"/>
  &nbsp;&nbsp;
  <img src="demo images/testing.png" alt="Testing Mode" width="480"/>
</p>

- **Left:** Training mode, where the neural network is learning to recognize new characters.
- **Right:** Testing mode, where the trained network predicts user-drawn characters.

## 🙌 Acknowledgments

- **Java AWT** – For the lightweight UI framework
- **Neural Network community** – For tutorials and foundational math
- **Professor T. Henry** – For project support and feedback
- **Open source inspiration** – For general architecture ideas and optimizations
