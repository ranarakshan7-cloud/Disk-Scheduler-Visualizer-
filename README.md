# Disk Scheduling Visualizer

A Python-based GUI application that visualizes and compares different disk scheduling algorithms used in Operating Systems. It helps users understand disk head movement, request servicing order, and seek performance through graphical visualization.

## Features

- Visual representation of disk head movement.
- Supports multiple disk scheduling algorithms.
- Displays seek sequence and total head movement.
- Graphical comparison of scheduling strategies.
- Interactive GUI built with Tkinter.

## Algorithms Implemented

- FCFS (First Come First Serve)
- SSTF (Shortest Seek Time First)
- SCAN
- LOOK
- C-SCAN (Circular SCAN)
- C-LOOK (Circular LOOK)

## Technologies Used

- Python
- Tkinter
- Matplotlib

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Disk-Scheduling-Visualizer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Disk-Scheduling-Visualizer
   ```

3. Install the required dependencies:

   ```bash
   pip install matplotlib
   ```

4. Run the application:

   ```bash
   python main.py
   ```

## Project Objective

The objective of this project is to provide an interactive learning tool for understanding disk scheduling algorithms, their working mechanisms, and how they optimize disk head movement and seek operations.

## Future Improvements

- Add algorithm performance comparison charts.
- Improve UI design and responsiveness.
- Add average seek time analysis.
- Support dynamic disk request input.

## License

This project is intended for educational purposes.
