# Chromospheric-Vortex
A mesmerizing rainbow vortex animation created with Python's Turtle graphics library.
🌀 Chromospheric Vortex
📖 Overview
A mesmerizing, animated rainbow vortex generated using Python's built-in turtle graphics library. The script dynamically shifts colors using the HSV color model and alters the pen width using a mathematical sine wave, creating a stunning "chromospheric" visual effect.

✨ Key Features
Rainbow Color Shifting: Smoothly transitions through the entire color spectrum using colorsys.
Dynamic Line Width: The thickness of the lines pulses using a math.sin wave calculation.
Optimized Rendering: Uses screen.tracer() to skip frames, making the animation run much faster and smoother.
Safe Exit: Includes a try/except block so the program closes gracefully if you click the 'X' to close the window early.
🛠️ Tech Stack
Python 3
turtle (Built-in Python module)
colorsys (Built-in Python module)
math (Built-in Python module)
⚡ How to Run
Because this uses Python's turtle module, it opens a separate graphical window. It will not work in a standard Google Colab notebook.

Download the vortex.py file from this repository.
Make sure you have Python installed on your computer.
Open your terminal or command prompt.
Navigate to where you saved the file and run:
python vortex.py
