# 🖥️ Operating Systems Lab Assignments (OS_LAB_ASSIGN)

This repository contains all Operating Systems Lab assignments completed as part of the B.Tech CSE (Data Science) curriculum.  
Each assignment demonstrates core OS concepts such as **process creation**, **IPC**, **CPU scheduling**, **system calls**, **process lifecycle**, and **shell scripting**.

---

## 👤 Student Information
- **Name:** yash chauhan  
- **Program:** B.Tech CSE (Data Science)  
- **Enrollment No:** 2301420059 

---

# 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| **Assignment1/** | Core OS concepts: process creation, IPC, file handling, zombies/orphans, priority scheduling |
| **Assignment2/** | OS boot simulation, multiprocessing, logging, process lifecycle |
| **Assignment3_Scheduling/** | CPU scheduling algorithms (FCFS, SJF, SRTF, RR) |
| **Assignment4/** | Shell scripting, system info extraction, IPC, OS utilities, exception handling |

---

# 🧪 Assignment Summaries

## **📘 Assignment 1 – Process Creation, IPC & Basic OS Concepts**
Includes:
- `task1.py` – Process creation using `fork()`
- `task2.py` – IPC with pipes/queues
- `task3.py` – File handling & system call emulation
- `task4.py` – Zombie & orphan process demonstration
- `task5.py` – Priority scheduling simulation

---

## **📘 Assignment 2 – System Boot, Logging & Process Lifecycle**
Includes:
- `subtask1.py` – OS boot sequence
- `subtask2.py` – Multiprocessing process creation
- `subtask3.py` – Logging system
- `subtask4.py` – Graceful shutdown simulation  
- `process_log.txt` – Output logs

---

## **📘 Assignment 3 – CPU Scheduling Algorithms**
Includes:
- `fcfs.py` – First Come First Serve
- `sjf.py` – Shortest Job First (Non-preemptive)
- `srtf.py` – Shortest Remaining Time First
- `rr.py` – Round Robin

---

## **📘 Assignment 4 – Shell Scripting, IPC & OS Utilities**
Includes:
- `script1.py`, `script2.py`, `script3.py`
- `task1.py`, `task2.py`, `task3_exc.py`, `task3_ipc.py`, `task4_detect.py`
- `system.info.sh` – System info shell script

---

## 🔹 **Run Assignment 1**

```bash
cd Assignment1

python3 task1.py
python3 task2.py
python3 task3.py
python3 task4.py
python3 task5.py


cd ../Assignment2

python3 subtask1.py     # OS boot simulation
python3 subtask2.py     # Process creation
python3 subtask3.py     # Logging system
python3 subtask4.py     # Process shutdown

cd ../Assignment3_Scheduling

python3 fcfs.py      # First Come First Serve
python3 sjf.py       # Shortest Job First (Non-preemptive)
python3 srtf.py      # Shortest Remaining Time First (Preemptive)
python3 rr.py        # Round Robin Scheduling

cd ../Assignment4

python3 script1.py
python3 script2.py
python3 script3.py

python3 task1.py        # OS operations + exceptions
python3 task2.py        # Process creation & handling
python3 task3_exc.py    # Exception handling
python3 task3_ipc.py    # IPC demonstration
python3 task4_detect.py # System detection/monitoring
