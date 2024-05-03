# Visual-Maze-Solver

Maze Solver Project Project Overview: The Maze Solver project is an exciting and challenging exploration into the world of computer science and algorithms. The goal of this project is to create a program that can solve a given maze, finding the optimal path from the starting point to the exit. 

## Features

- Allows uploading custom maze images in JPG, JPEG, or PNG format.
- Provides sliders to position the start and end points on the maze image.
- Utilizes Dijkstra's algorithm to find the shortest path from the start to the end point.
- Visualizes the solved maze by highlighting the shortest path.

## How to Use

1. **Choose an Image**: Upload a maze image or use the default maze provided.
2. **Position Start and End Points**: Use the sliders on the right to set the start and end points on the maze.
3. **Solve Maze**: Click the "Solve Maze" button to find the shortest path.
4. **View Solution**: The solved maze with the shortest path highlighted will be displayed.

## Requirements

- Python 3.x
- OpenCV
- Matplotlib
- Numpy
- Streamlit
- HTML

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/jayant-0000/maze-master
   ```

2. Navigate to the project directory:

   ```bash
   cd maze-solver
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Web-App-Interface

- Web-App-Interface is provided to interact with the maze solver.
![Default-Ui](/images/web-app.png)

- Uploading & Marking the start and end points on the maze image.
![Marked-State-Ui](/images/marked-state-ui.png)

- Solved maze with the shortest path highlighted.
![Default-Ui](/images/solved-state-ui.png)

## Usage

Run the Streamlit app:

```bash
streamlit run index.py
```

- Open the provided URL in your browser to access the web interface.
- Upload a maze image or use the default maze.
- Set the start and end points using the sliders.
- Click the "Solve Maze" button to find the shortest path.
- View the solved maze with the shortest path highlighted.
- To exit the app, press `Ctrl+C` in the terminal.

## Example

| ![Unsolved-State](/images/marked-state.png) | ![Solved-state](/images/solved-state.png) |
| ------------------------------------------- | ----------------------------------------- |
| _Unsolved-State-With-Markings_              | _Solved-state-with-Path_                  |

## Credits

- Maze solving algorithm based on Dijkstra's algorithm
- Streamlit for the interactive web interface
- OpenCV for image processing
- Matplotlib for visualization
- Numpy for numerical operations
- Developed by [Jayanth & Team](https://github.com/jayant-0000/) as part of Mini Project [@sitams](https://sitams.org/)
