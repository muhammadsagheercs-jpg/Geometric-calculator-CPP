📐 Geometric Calculator — C++

A menu-driven C++ console application for computing area, perimeter, surface area, and volume of common 2D and 3D geometric shapes.

Table of Contents
Overview
Features
Supported Shapes
Technologies
Getting Started
Project Structure
Documentation
Learning Outcomes
Roadmap
Author
Overview

Geometric Calculator is a console-based C++ application that makes geometric computations simple and interactive. Users select a shape from a structured menu, enter the required dimensions, and receive instant results — no external libraries or setup required.

Goal: Demonstrate core C++ programming fundamentals — mathematical logic, user interaction, and structured program design — through a practical, real-world application.

Features
Interactive, menu-driven console interface
Calculations for both 2D and 3D geometric shapes
User-supplied dimensions with immediate output
Clean program flow using functions and conditional logic
Beginner-friendly codebase with clear structure
Supported Shapes
2D Shapes
Shape	Calculations
Circle	Area, Circumference
Square	Area, Perimeter
Rectangle	Area, Perimeter
Triangle	Area, Perimeter
3D Shapes
Shape	Calculations
Sphere	Surface Area, Volume
Cylinder	Surface Area, Volume
Cone	Surface Area, Volume
Cube	Surface Area, Volume
Cuboid	Surface Area, Volume
Technologies
Language: C++ (C++11 or later recommended)
Standard Library: <iostream>, <cmath>
Environment: Terminal / Command Prompt
Getting Started
Prerequisites
A C++ compiler (e.g., g++, clang++, or MSVC)
Git (optional, for cloning)
Installation

1. Clone the repository

bash
git clone https://github.com/your-username/geometric-calculator-cpp.git
cd geometric-calculator-cpp

2. Compile

bash
g++ src/project.cpp -o geometric-calculator

3. Run

On Linux / macOS:

bash
./geometric-calculator

On Windows:

bash
geometric-calculator.exe
Program Flow
Main Menu
├── 2D Shapes
│   ├── Circle
│   ├── Square
│   ├── Rectangle
│   └── Triangle
└── 3D Shapes
    ├── Sphere
    ├── Cylinder
    ├── Cone
    ├── Cube
    └── Cuboid
        └── Enter dimensions → Calculate → Display result
Project Structure
geometric-calculator-cpp/
├── src/
│   └── project.cpp
├── screenshots/
│   ├── main-menu.png
│   ├── cone-volume-calculation.png
│   └── project-showcase.png
├── project-proposal/
│   └── Geometric-Calculator-Project-Proposal.pdf
├── project-report/
│   └── Geometric-Calculator-Project-Report.pdf
├── README.md
└── LICENSE
Documentation
Document	Description
Project Proposal	Outlines objectives, scope, and planned functionality
Project Report	Details implementation, geometric formulas, design decisions, and outcomes
Learning Outcomes

This project reinforced understanding of:

Problem Solving — Translating mathematical formulas into programming logic
C++ Fundamentals — Variables, data types, arithmetic, conditionals, loops, and functions
Mathematical Logic — Implementing geometric computations programmatically
Program Structure — Organizing a multi-option, menu-driven console application
User Interaction — Designing a clear and intuitive command-line interface
Roadmap

Planned improvements for future versions:

 Input validation and error handling
 Calculation history with session log
 Export results to a file
 Graphical User Interface (GUI)
 Web-based version
 Mobile application
Author

Sagheer Computer Science Student Interests: Software Development · Web Development · Artificial Intelligence

If you find this project helpful, consider giving it a star on GitHub.
