# 💽 OS Disk Scheduling Visualizer

An interactive web-based visualization tool for understanding and comparing different disk scheduling algorithms used in Operating Systems.

## 📌 About the Project

The **OS Disk Scheduling Visualizer** demonstrates how disk scheduling algorithms manage disk requests and determine the order in which requests are serviced.

It helps students understand disk head movement, seek time, request servicing order, and the differences between various disk scheduling techniques through visual representations.

## ✨ Features

- Interactive disk scheduling visualization.
- Enter custom disk request sequences.
- Set the initial disk head position.
- Visualize disk head movement.
- View the request servicing order.
- Compare the working of different scheduling algorithms.
- Simple and user-friendly interface.

## 🧠 Algorithms

The project covers the following disk scheduling algorithms:

1. **FCFS (First Come First Serve)** – Processes disk requests in the order they arrive.
2. **SSTF (Shortest Seek Time First)** – Selects the request closest to the current head position.
3. **SCAN (Elevator Algorithm)** – Moves the disk head in one direction, servicing requests before reversing.
4. **C-SCAN (Circular SCAN)** – Services requests in one direction and returns to the beginning.
5. **LOOK** – Similar to SCAN but reverses at the last pending request.
6. **C-LOOK** – Similar to C-SCAN but jumps between the last and first pending requests.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ashthaf/os-disk-scheduling-visualizer.git
```

### 2. Navigate to the project directory

```bash
cd os-disk-scheduling-visualizer
```

### 3. Run the project

Open `index.html` in your web browser.

No additional installation is required.

## 📂 Project Structure

```text
os-disk-scheduling-visualizer/
│
├── index.html
└── README.md
```

*The structure may be updated as the project develops.*

## 🎯 Learning Objectives

- Understand disk scheduling techniques.
- Visualize disk head movement.
- Learn how different algorithms service disk requests.
- Compare disk scheduling approaches.
- Understand seek operations in Operating Systems.

## 👨‍💻 Author

**Abdull Ashthaf CK**

- GitHub: [@ashthaf](https://github.com/ashthaf)
- LinkedIn: [Abdull Ashthaf](https://www.linkedin.com/in/abdull-ashthaf-ck-866889291/)

---

⭐ If you find this project useful, consider giving it a star!
