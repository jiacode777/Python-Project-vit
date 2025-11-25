# Smart Routine Optimizer (SRO)

The **Smart Routine Optimizer** is a productivity-based scheduling tool that generates an optimized daily routine for users based on their tasks, deadlines, priorities, and available time slots.
It uses simple scheduling logic and algorithms to create a practical timetable that fits real-life study or work requirements.

---

## 1. Overview

Students and working professionals often struggle to manage multiple tasks with different deadlines. The Smart Routine Optimizer takes user inputs and produces a structured plan for the day or week, helping them stay disciplined and organized.

This project applies core programming concepts such as:

* Modular programming
* Data structures
* Sorting and scheduling algorithms
* File handling (optional)

---

## 2. Features

* Add tasks with:

  * Task Name
  * Required Time
  * Priority (High / Medium / Low)
  * Deadline (Date)
* Add daily time slots when the user is free.
* Automatically schedules tasks based on:

  * Priority
  * Earliest Deadline First (EDF)
  * Available time
* Generates a clean routine output.
* Saves schedule to text/JSON file (optional).
* Simple, terminal-based interface.

---
SRO/
├── data/
│   ├── input/
│   │   ├── sample_input.json
│   │   └── schedule.json
│   └── output/
│       ├── json/
│       └── txt/
├── src/
│   ├── __init__.py
│   ├── input_handler.py
│   ├── scheduler.py
│   ├── tasks.py
│   ├── output.py
│   └── main.py
├── config/
│   └── settings.json
├── tests/                        # (future unit tests)
├── .gitignore
├── requirements.txt              # if you use external packages
└── README.md

## 4. How It Works

1. User enters tasks with full details.
2. Tasks are sorted using:

   * Priority mapping (High > Medium > Low)
   * Deadline ordering (Earliest first)
3. Time slots are processed.
4. The scheduler assigns tasks into available hours.
5. Final routine is displayed and optionally saved.

---

## 5. How to Run

1. Install Python 3.13
2. Clone the repository:

   ```
   git clone <your-repo-link>
   ```
3. Run the main file:

   ```
   python main.py
   ```
4. Follow the instructions on the screen.

---

## 6. Example Output

```
Generated Routine for 21 November 2025:

09:00 - 10:30  :  Study Maths (High Priority)
10:30 - 11:00  :  Break
11:00 - 12:00  :  Complete Assignment (Medium Priority)
14:00 - 15:00  :  Project Work (Low Priority)
```
# SRO - Scheduler & Copy Tool


<img width="1324" height="535" alt="output" src="https://github.com/user-attachments/assets/4e582dee-1b0b-434b-b225-7acf9137a9e9" />

Main interface running in VS Code

---

## 8. Limitations

* Only works with user-entered time slots.
* No GUI (currently command-line based).
* Doesn’t auto-handle overlapping deadlines.

---

## 9. Future Improvements

* Add a GUI or web interface.
* Integrate notifications/reminders.
* Add calendar export (.ics).
* Add optimization using weighted scheduling.

---

## 10. Author

Developed by Naivedya Singh 25BAI10770

---

## 11. License

This project is mine Naivedya Singh and cannot be used 

