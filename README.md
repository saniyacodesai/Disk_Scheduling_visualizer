# 💽 Disk Scheduling Simulator

An interactive web-based simulator to visualize and compare different disk scheduling algorithms used in Operating Systems.

---

## 🚀 Features

* Supports multiple disk scheduling algorithms:

  * FCFS (First Come First Served)
  * SSTF (Shortest Seek Time First)
  * SCAN
  * C-SCAN
  * LOOK
  * C-LOOK

* Dynamic input for disk requests and head position

* Step-by-step animated execution

* Visual graph representation of head movement

* Calculates total seek time for each algorithm

* Highlights the **best algorithm (minimum seek time)**

---

## 🛠 Tech Stack

* HTML
* CSS
* JavaScript

---

## ▶ How to Run

1. Download or clone this repository
2. Open the file:

   ```
   disk-scheduling.html
   ```
3. Enter:

   * Number of disk requests
   * Request values
   * Initial head position
4. Click **Run All Algorithms**

---

## ⚙ Algorithms Explained

* **FCFS** → Processes requests in order of arrival
* **SSTF** → Selects the closest request to current head
* **SCAN** → Moves in one direction, then reverses (elevator)
* **C-SCAN** → Moves in one direction and jumps back
* **LOOK** → Like SCAN but stops at last request
* **C-LOOK** → Like C-SCAN but only goes till last request

---

## 🎯 Purpose

This project helps students:

* Understand disk scheduling concepts visually
* Compare algorithm performance
* Prepare for Operating Systems practicals and viva

---

## ⚠ Notes

* Disk range is assumed between **0 – 199**
* All algorithms are implemented for demonstration and learning purposes

---

## 📌 Future Improvements

* Direction control for SCAN / LOOK
* Custom disk size input
* Better UI controls and validation
* Performance comparison charts

---

## 👩‍💻 Author
#Ninii<3

Created as part of Operating Systems practical work.
