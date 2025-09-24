# Car Park Embedded System (C Programming Lab Project)

This repository demonstrates an embedded system implementation of a Car Park controller using C programming.
The project was originally developed as a lab exercise and has been adapted into a GitHub research-style portfolio to showcase programming and embedded systems design skills.

---

## Repository Structure

```
car-park-embedded-system/
├── README.md
├── LICENSE
├── .gitignore
├── report/
│   └── CarPark_LabExercise.pdf    # Anonymized version of the original lab report
├── code/
│   └── carpark_main.c             # Main program in C (add your code here)
└── figures/
    └── screenshots.png            # Simulation/circuit screenshots (optional)
```

---

## Project Overview

The project focuses on designing a Car Park controller with the following features:

- Entry/exit control for vehicles
- Counter for available parking slots
- Gate simulation using LEDs / Proteus
- C programming structures: if, while, macros, and functions
- Demonstration of modular programming practices

---

## Key Features

1. C Programming Concepts
   - Conditional statements (if / else)
   - Loops (while)
   - Function prototypes
   - Use of macros vs functions

2. Embedded System Implementation
   - Input sensors (simulated buttons)
   - Output signals (LEDs, gate control)
   - Counter for parked cars

3. Simulation
   - Proteus schematic for car park system
   - Debugging using simple test cases

---

## Example Code Snippet

```c
#define MAX_SPACES 50

int available = MAX_SPACES;

void car_enter() {
    if (available > 0) {
        available--;
        printf("Car entered. Spaces left: %d\n", available);
    } else {
        printf("Car park full!\n");
    }
}
```

---

## Example Figures

(Place images in the `figures/` folder and link them here)

- Proteus schematic of car park system
- Simulation screenshot with gate open/closed
- Console output showing available spaces

---

## How to Use

1. Open the `report/CarPark_LabExercise.pdf` for a full explanation (anonymized version).
2. Compile `code/carpark_main.c` in any C environment or microcontroller toolchain.
3. Run Proteus simulation for embedded demonstration (optional).

---

## Notes

- Original work was prepared as a lab exercise.
- Sensitive information (student name/ID, academic integrity declaration) should be anonymized before publishing.
- This repository is intended as a portfolio project to demonstrate embedded C programming and system design skills.

---

## Author

Jinyan Yang — MSc in Renewable Energy Systems
