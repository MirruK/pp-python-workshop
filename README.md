# Python Pandas EDA Workshop

This repository is designed for a Python Pandas Exploratory Data Analysis (EDA) workshop. Follow the steps below to set up your environment and get started.

---

## Prerequisites

1. **Install Poetry**  
    Poetry is used for dependency management. Install it by following the instructions on the [Poetry website](https://python-poetry.org/docs/#installation).

    Alternatively, you can use the following command:
    ```bash
    curl -sSL https://install.python-poetry.org | python3 -
    ```

2. **Install VS Code Extensions**  
    Install the following extensions in Visual Studio Code:
    - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

---

## Setup Instructions

1. **Clone the Repository**  
    Clone this repository to your local machine:
    ```bash
    git clone <repository-url>
    cd pp-python-workshop
    ```

2. **Install Dependencies**  
    Use Poetry to install the required dependencies:
    ```bash
    poetry install
    ```

3. **Start JupyterLab**  
    Start the JupyterLab server using Poetry:
    ```bash
    poetry run jupyter lab
    ```

4. **Open the Notebook in VS Code**  
    - Open the repository folder in VS Code.
    - Navigate to the `spotify.ipynb` file and open it.

5. **Connect to the Jupyter Kernel**  
    - In the notebook, click on the kernel selector in the top-right corner.
    - Select the Python environment created by Poetry (e.g., `.venv`).

---

You are now ready to explore the notebooks and perform EDA!  