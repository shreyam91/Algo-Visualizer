# Algorithm Visualizer

Welcome to the **Algorithm Visualizer** project! This is an interactive web-based tool designed to help users visualize various algorithms in computer science. The goal of this project is to provide an intuitive and engaging way to understand how different algorithms work by animating their steps and processes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Algorithms Supported](#algorithms-supported)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Algorithm Visualizer helps users understand complex algorithms by visualizing their steps in real-time. The project uses JavaScript, HTML, and CSS to animate the algorithms and show the data manipulation at each step. It's a great resource for students, educators, and anyone looking to understand algorithmic logic in a more visual and interactive manner.

The visualizer is designed to cover a variety of algorithms, including sorting, searching, and graph-related algorithms, with plans to add more in the future.

## Features

- **Interactive Visualizations**: Step-by-step animations of algorithms, allowing you to see how the data is manipulated.
- **Customizable Input**: Allow users to customize the input data (e.g., array size, values, etc.).
- **Multiple Algorithms**: Visualizations for sorting algorithms, graph algorithms, and more.
- **Speed Control**: Control the speed of algorithm execution to observe each step more closely.
- **Mobile-Friendly**: Responsive design for use on desktops, tablets, and mobile devices.

## Getting Started

To get started with this project, you'll need the following:

- A modern web browser (e.g., Chrome, Firefox, Edge)
- Basic knowledge of algorithms and their operations (optional, but recommended)

### Steps to Run Locally:

1. Clone this repository:
  

2. Navigate to the project directory:
    ```bash
    cd algorithm-visualizer
    ```

3. Open the `index.html` file in your browser to launch the application.

4. (Optional) If you'd like to make changes to the project locally, you can open the files in your preferred code editor (e.g., Visual Studio Code).


### Key Files:
- **index.html**: The main HTML file that loads the application in the browser.
- **styles.css**: Contains the styles for the visualizer's UI.
- **main.js**: Handles the user interface interactions and links algorithms with the visualizer.
- **algorithms/**: Directory containing the algorithm logic for various sorting and graph algorithms.
- **utils.js**: Contains utility functions for animations and visual effects.

## Algorithms Supported

Currently, the visualizer supports the following algorithms:

- **Sorting Algorithms**:
    - Bubble Sort
    - Quick Sort
    - Merge Sort
    - Selection Sort
    - Insertion Sort

- **Searching Algorithms**:
    - Binary Search
    - Linear Search

- **Graph Algorithms**:
    - Depth First Search (DFS)
    - Breadth First Search (BFS)
    
We plan to add more algorithms in the future, including but not limited to:

- Dijkstra's Shortest Path Algorithm
- A* Search Algorithm
- Heap Sort
- Radix Sort

## How to Use

Once you have the visualizer running, follow these steps:

1. **Choose an Algorithm**: Select the algorithm you want to visualize from the dropdown menu at the top of the page (e.g., Quick Sort, BFS, etc.).
2. **Customize Input**: Adjust the input data. For example, you can modify the size of an array or the values in a list.
3. **Start Visualization**: Press the "Start" button to begin the animation. You’ll see each step of the algorithm being executed, with the data being manipulated in real-time.
4. **Control Speed**: Use the speed slider to control how fast the algorithm runs. You can pause or restart the visualization anytime.
5. **Reset**: Click the "Reset" button to clear the current data and start with a fresh set.

## Contributing

We welcome contributions from the community! If you'd like to add new algorithms, fix bugs, or improve the user interface, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new algorithm'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

Before submitting a pull request, please make sure your code follows the project’s coding style and is thoroughly tested.

## License

This project is open-source and available under the [MIT License](LICENSE).
