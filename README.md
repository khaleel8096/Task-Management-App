# Task Management App

A simple Task Management App implemented in Python with a basic machine learning model for task prioritization.

## Overview

This Task Management App allows users to add tasks, remove tasks, list tasks, and get recommendations for high-priority tasks based on a simple machine learning model. The app utilizes a Multinomial Naive Bayes classifier to predict task priorities.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages: pandas, scikit-learn

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/task-management-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd task-management-app
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main application:

    ```bash
    python task_manager.py
    ```

2. Follow the on-screen menu to perform various tasks:
   - **Add Task:** Add a new task with a description and priority (Low/Medium/High).
   - **Remove Task:** Remove a task by entering its description.
   - **List Tasks:** Display all tasks in the system.
   - **Recommend Task:** Get a recommendation for a high-priority task.

3. Exit the application when done.

## File Structure

- **`task_manager.py`**: Main script containing the application logic.
- **`tasks.csv`**: CSV file to store task data.
- **`recommendations.csv`**: CSV file to store recommended tasks.

## Acknowledgments

- This project is a basic implementation and can be extended for more advanced features.

Feel free to contribute or provide feedback!

---

Remember to replace "your-username" in the repository URL with your actual GitHub username. This README provides a brief introduction, installation instructions, basic usage, and acknowledgments. You can enhance it further with specific details about the machine learning model, error handling, or any other features you implement.
