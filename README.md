# Keyboard Input Logging Demo (Python)

## Overview

This project demonstrates how keyboard events can be captured in a Python program and written to a file.
The purpose of this project is to understand **event listeners, input handling, and file logging**.

It uses the `pynput` library to detect keyboard input events and save them to a text file for demonstration purposes.

---

## Technologies Used

* Python
* pynput library
* File handling

---

## Features

* Detects keyboard key press events
* Logs the pressed keys into a text file
* Demonstrates how event listeners work in Python

---

## How It Works

1. The program starts a keyboard listener using the pynput library.
2. Every key press event triggers a function.
3. The function writes the key information into a log file.
4. Each key press is saved on a new line.

---

## Installation

Install the required library:

```
pip install pynput
```

---

## Running the Program

Run the script using Python:

```
python keylogger.py
```

A file named **keylog.txt** will be created where key events are recorded.

---

## Example Log Output

```
'a'
'b'
Key.space
'c'
```

---

## Educational Purpose

This project is intended only for **learning how keyboard event listeners work in software development**.

Running programs that monitor user input without permission may violate privacy laws and ethical guidelines.

---

## Possible Improvements

* Add timestamps to each logged key
* Filter special keys
* Build a GUI to visualize key presses
* Implement permission or notification systems

---

## Author

Ganesh Mane
Computer Science Student interested in Cybersecurity, Cloud Computing, DevOps, and Web Development.
