# Enchanted Forest Treasure Hunt
Enchanted forest treasure hunt! Guide adventurer with A* or UCS to find treasure. Compare pathfinding efficiency.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Cloning The Project](#cloning-the-project)
- [Running The Project](#running-the-project)
- [License](#license)
- [Contact](#contact)

## Introduction

Welcome to the "Treasure Hunt In The Enchanted Forest" project! This Python script embarks on an exciting adventure through an enchanted forest filled with mysteries and treasures. The project utilizes various algorithms to navigate through the forest, avoid obstacles, and discover hidden treasures.

## Problem Statement

The "Treasure Hunt In The Enchanted Forest" project addresses the problem of navigating through a complex environment, represented as a grid, to find the shortest path from a starting position to an end position while avoiding obstacles and dealing with unpredictable elements such as animals. The project utilizes two popular search algorithms, A* (A-star) and UCS (Uniform Cost Search), to efficiently find the optimal path through the forest.

The key challenges tackled by this project include:

- Finding the shortest path while avoiding obstacles: The forest environment contains various obstacles that obstruct the path of the treasure hunter. The project's algorithms aim to find a path that circumvents these obstacles to reach the treasure.

- Dealing with unpredictable elements: The presence of animals introduces uncertainty into the treasure hunt adventure. The project incorporates random factors to simulate encounters with animals, requiring the treasure hunter to adapt their pathfinding strategy accordingly.

By employing A* and UCS algorithms, the project offers a solution to these challenges, allowing users to embark on an exciting treasure hunt adventure in the enchanted forest while experiencing the effectiveness of different pathfinding techniques.

## Features

- **Graphical User Interface (GUI)**: Enjoy a visually appealing treasure hunt adventure with a user-friendly GUI.
  
- **Dynamic Grid**: Navigate through a dynamically generated grid filled with obstacles, animals, and treasures.
  
- **Search Algorithms**: Choose between A* (A-star) search or Uniform Cost Search to find the shortest path to the treasure.
  
- **Obstacle Avoidance**: Strategically plan your route to bypass obstacles and reach the treasure safely.
  
- **Animal Encounters**: Encounter friendly and mischievous forest creatures along your journey, each with its own unique behavior.
  
- **Real-time Feedback**: Receive real-time feedback on your progress and encounters, including total cost incurred and paths taken.
- **Cost Calculation**: The program determines the cost associated with moving to a neighboring block based on its type. The `calculate_cost` method assigns a cost value to different block types:

  - For a "free" block type, the cost is randomly generated within the range of -3 to -1, indicating the ease of movement.
  
  - If the block type is an "animal", the program simulates the probability of encountering the animal. If the probability of encountering the animal is less than 0.8, indicating survival, the cost is randomly generated within the range of -3 to -1. However, if the encounter results in death, the cost is randomly generated within the range of -4 to -2, reflecting the higher risk involved.
  
  - For other block types (e.g., obstacles), the cost is set to 0, indicating that movement to such blocks is not possible or feasible.
  
- **Customization Options**: Customize the game environment with adjustable grid dimensions.
## Getting Started

### Prerequisites

Before running the "Treasure Hunt In The Enchanted Forest" project, make sure you have the following prerequisites installed:

- **Python**: Ensure that Python is installed on your system. You can download and install Python from the official [Python website](https://www.python.org/).

- **PIL (Python Imaging Library)**: PIL is used for image processing in the project. You can install it via pip using the following command:
  
  ```bash
  pip install pillow
  ```

- **Tkinter**: Tkinter is included with most Python installations, but if it's not available, you may need to install it separately. Tkinter is used for creating the graphical user interface (GUI) in the project. You can install it via pip using the following command:
  
  ```bash
  pip install tk
  ```

## Cloning the Project
To get started with the project, follow these steps:

1. **Clone or download the project repository to your local machine:**
  ```bash
  git clone [repository_url]
  ```
2. **Navigate to the project directory:**
  ```bash
  cd Treasure_Hunt_In_The_Enchanted_Forest
  ```
## Running the project
Now that you have cloned the project repository, you can run the project in a Jupyter Notebook.
1. **Launch Jupyter Notebook by running the following command in your terminal:**

  ```bash
  jupyter notebook
  ```
2. **This will open a new browser window/tab with the Jupyter Notebook interface.**
3. **Navigate to the Jupyter Notebook file (Treasure_Hunt_In_The_Enchanted_Forest.ipynb) in the project directory.**
4. **Open the notebook and execute each cell sequentially by pressing Shift + Enter or by clicking the "Run" button in the Jupyter Notebook interface.**
5. **Follow any instructions or prompts within the notebook to interact with your project and proceed through the treasure hunt adventure.**
6. **Continue executing cells until you reach the end of the project or until you have completed the desired portion of the adventure.**
   
## License
Enchanted Forest Treasure Hunt is released under the [MIT License](LICENSE).

## Contact
If you have any questions, or feedback, or just want to get in touch, feel free to reach out via email:

- **Email:** ulwahabzain@gmail.com
