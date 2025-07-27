# 🎮 Tetris in Raylib

A simple, clean, and fully functional clone of the classic Tetris game, built using Raylib — a highly modular and easy-to-use C library for game development. This project is a great starting point for anyone learning game loops, rendering, and basic input handling in C with Raylib.


<img width="494" height="643" alt="s1" src="https://github.com/user-attachments/assets/d21a1c65-179f-4f3b-af46-c39bb1a3b34d" />


## 🚀 Features
Classic Tetris gameplay: falling blocks, line clearing, scoring

Responsive keyboard controls

Grid-based rendering with smooth visuals

Simple and readable game loop

Lightweight and fast — perfect for learning or expanding upon

## 🎮 Controls
Key	Action
← / →	Move block left/right
↓	Soft drop
↑	Rotate block
SPACE	Hard drop
R	Restart game
ESC	Exit

🛠️ Requirements
Raylib (version 4.0 or higher recommended)

C compiler (e.g., GCC)

Make (optional for Linux/Unix)

## 🔧 How to Build
Windows (Using MinGW)
bash
Copy
Edit
gcc main.c -o tetris.exe -lraylib -lwinmm -lgdi32
./tetris.exe
Linux
bash

## 🧠 What You'll Learn
How to structure a simple 2D game in C

Basics of rendering and input handling in Raylib

Logic for managing falling blocks and collision detection

Creating a grid-based game system
Copy
Edit
gcc main.c -o tetris -lraylib -lm -ldl -lpthread -lX11
./tetris
Make sure Raylib is properly installed on your system before compiling.
