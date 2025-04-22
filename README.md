# 🧵 Producer-Consumer Problem with POSIX Threads

This project demonstrates a classical **Producer-Consumer problem** solution using **POSIX threads (pthreads)** with **mutexes** and **condition variables** in C. The implementation mimics an RTOS-like behavior with real-time synchronization mechanisms.

---

## 🔧 Features

- **Thread-safe circular queue**
- **Mutex-protected** access to the shared buffer
- **Condition variables** to avoid busy-waiting
- **Simulated sensor data production and filtering**
- Infinite running producer and consumer tasks

---

## 📦 Files

- `main.c`: Core source file implementing the producer-consumer logic
- `Makefile`: *(optional)* A simple Makefile to compile the program
- `README.md`: This documentation

---

## 📌 Compilation

### With GCC (Linux/macOS):
```bash
gcc -o producer_consumer main.c -lpthread
