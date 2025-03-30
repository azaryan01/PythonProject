# PythonProject

This repository contains Python scripts and tests using **Pytest** to test various functions and features in Python.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/azaryan01/PythonProject.git
    cd PythonProject
    ```

2. (Optional) Set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Install **Pytest** if not installed already:
    ```bash
    pip install pytest
    ```

## Usage

1. Write test functions in files starting with `test_`, for example:
    ```python
    # test_example.py
    def test_addition():
        assert 1 + 1 == 2
    ```

2. Run tests using Pytest:
    ```bash
    pytest
    ```

   Pytest will automatically find and run all test functions.

3. To run a specific test:
    ```bash
    pytest test_example.py
    ```