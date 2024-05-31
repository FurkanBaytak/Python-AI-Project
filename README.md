# Python AI Project

This repository contains the programming assignments for the "CSE 3111 / CSE 3213 Artificial Intelligence" course at Manisa Celal Bayar University, Fall 2023. This one .ipynb file is the collection of all these three assesments.

## Table of Contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Assignments Description](#assignments-description)
  - [Assignment 1](#assignment-1)
  - [Assignment 2](#assignment-2)
  - [Assignment 3](#assignment-3)
- [Results](#results)
- [Discussion](#discussion)
- [Contributors](#contributors)
- [Project Report](#project-report)
- [License](#license)

## Introduction

This repository includes three programming assignments focused on different aspects of artificial intelligence, including state space search algorithms and heuristic evaluation. The assignments are implemented in Python and cover the N-Queens problem.

## Project Description

The programming assignments in this repository explore various AI techniques and algorithms through the classic N-Queens problem. Each assignment builds on the previous one, introducing more complexity and requiring the application of different AI strategies. The goal is to find a configuration of N queens on an N×N chessboard where no two queens threaten each other. The assignments leverage state space search algorithms and heuristic evaluations to solve this problem efficiently. The project aims to provide practical experience with AI concepts and improve problem-solving skills.

## Project Structure

The project files are organized as follows:

```bash
  /Python-AI-Project
  │
  ├── AI_PA.ipynb
  ├── AI_PA_Report.pdf
  ├── PA_Base
  │ └── AI_PA1_Base.ipynb
  └── PA_Assesment_Papers
  ├── AI_PA1.pdf
  ├── AI_PA2.pdf
  └── AI_PA3.pdf
```

## Setup

To run this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/FurkanBaytak/Python-AI-Project.git
    cd Python-AI-Project
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

This one .ipynb file is the collection of all these three assesments. To start Jupyter Notebook, use the following command:
    ```bash
    jupyter notebook
    ```
Then, open the desired `.ipynb` file to view and execute the code.

## Assignments Description

### Assignment 1

**Problem Formulation:**
- State Specification: Status represents the current arrangement of queens on the chessboard.
- Initial State: User-defined or randomly generated initial placement of queens.
- Possible Actions: Movements of queens within their columns.
- Transition Model: Describes how actions change state.
- Goal Test: Checks if no two queens threaten each other.
- Path Cost: Heuristic function calculating the number of attacking queen pairs.

- [Assesment 1](https://github.com/FurkanBaytak/Python-AI-Project/blob/main/PA_Assesments_Papers/AI_PA1.pdf)

### Assignment 2

**Problem Formulation:**
- Similar to Assignment 1 but with different constraints and initial setups.

- [Assesment 2](https://github.com/FurkanBaytak/Python-AI-Project/blob/main/PA_Assesments_Papers/AI_PA2.pdf)

### Assignment 3

**Problem Formulation:**
- Extends the problem to larger board sizes and involves more complex heuristic evaluations.

- [Assesment 1](https://github.com/FurkanBaytak/Python-AI-Project/blob/main/PA_Assesments_Papers/AI_PA3.pdf)

## Results

The results section includes outputs from the simulations, showcasing the performance of different algorithms in solving the N-Queens problem. This one .ipynb file is the collection of all these three assesments.

## Discussion

### Completeness
- Evaluates whether the algorithms are guaranteed to find a solution.

### Optimality
- Discusses if the algorithms are guaranteed to find the best solution.

### Time and Space Complexity
- Compares the time and space requirements of different algorithms.

### Effect of Depth Limit in Depth Limited Search
- Analyzes the impact of setting depth limits in search algorithms.

### Comparison of Local Search Algorithms to Traditional Search Algorithms
- Discusses the effectiveness and limitations of local search algorithms compared to traditional ones.

## Contributors

- [Furkan ÖZKAYA](https://github.com/Elhier0)
- [Furkan BAYTAK](https://github.com/FurkanBaytak)
- [Sıla Naz ASLAN](https://github.com/silanazaslan)

## Project Report

For detailed information about the project and the report, you can view [this link](https://github.com/FurkanBaytak/Python-AI-Project/blob/main/AI_PA_Report.pdf).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

