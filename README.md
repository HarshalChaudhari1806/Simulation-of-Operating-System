# Simulation of Operating System

This project simulates key components of an Operating System including job scheduling, memory management, and execution control. It is structured in multiple phases, implemented in C++.

## 🗂️ Project Structure

Simulation of Operating System/
├── input.txt # Input job definitions
├── job1ALL.txt # Combined job input
├── job1ALL_op.txt # Output of job1ALL processing
├── OS_phase1.pdf # Phase 1 documentation/report
├── output.txt # Output after simulation
├── phase1.cpp # Source code for Phase 1 of simulation
├── phase2.cpp # Source code for Phase 2 of simulation

## 📌 Description

The project is divided into two phases:

### 🔹 Phase 1 (Implemented in `phase1.cpp`)

- Parses job input from `input.txt` or `job1ALL.txt`
- Simulates basic job control operations like:
  - Job ID detection
  - Start/End markers
  - Memory allocation preparation

### 🔹 Phase 2 (Implemented in `phase2.cpp`)

- Simulates execution of the parsed jobs
- Handles I/O operations, job scheduling, and memory allocation
- Produces detailed job execution output to `output.txt`

## 🚀 How to Compile and Run

Make sure you have a C++ compiler installed (`g++` recommended).

```sh
g++ phase1.cpp -o phase1
./phase1

g++ phase2.cpp -o phase2
./phase2
Ensure that the required input files (input.txt, job1ALL.txt) are present in the same directory before running the programs.

📄 Documentation
Refer to OS_phase1.pdf for the detailed problem statement, algorithm description, and system architecture overview.

## ✅ Sample Flow
Input: Job control data from input.txt or job1ALL.txt

Phase 1: Parsing and preparation

Phase 2: Execution and output generation

Output: Results saved in output.txt and job1ALL_op.txt

Developed for: Operating Systems Course Simulation Project
Language: C++#
