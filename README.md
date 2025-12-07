# AI-Powered Deadlock Detection System

**Author:** Gaurav Kumar  
**Course:** Operating Systems  
**Language:** C  
**File:** `deadlock_system.c`

---

## Project summary

This project simulates resource allocation in an operating system and combines Banker's deadlock detection with a lightweight AI heuristic that predicts deadlock probability and suggests/prevents actions (delay, preempt, terminate). It demonstrates detection, prediction, and resolution of deadlocks in a simulated environment.

---

## Features

- Banker's safety algorithm for deadlock detection
- Simulation loop that generates resource requests
- Lightweight AI heuristic (`aiPredictDeadlockProb()`) that computes a probability of deadlock from trends
- Resolution strategies: preemption and process termination
- CLI monitoring output per simulation cycle

---

## Files

- `deadlock_system.c` — main program (C)
- `README.md` — this file
- `.gitignore` — recommended ignores for build artifacts
- `requirements.txt` — optional Python deps (if you add Python analysis)

---

## How to build & run (Windows PowerShell / Linux)

1. Compile:
```bash
gcc deadlock_system.c -o deadlock_system
