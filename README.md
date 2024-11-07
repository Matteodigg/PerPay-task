# PerPay-task

This project contains results for the PerPay task - Author: Matteo Di Giovannantonio.

## Installation

To install the required modules follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Matteodigg/PerPay-task.git
    ```

2. **Create a Virtual Environment**:

    ```bash
    cd PerPay-task/
    python -m venv perpay_venv
    ```

3. **Activate the Virtual Environment** (for Unix-based systems):

    ```bash
    source perpay_venv/bin/activate
    ```

4. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

5. **Add the virtual environment to Jupyter Lab**: register the virtual environment as a kernel so it appears as an option in Jupyter Lab:

    ```bash
    python -m ipykernel install --user --name=perpay_venv --display-name "PerPay_env_MDG_task"
    ```

6. **Use the PerPay_env_MDG_task kernel**: use the registered kernel in Jupyter to run code in the notebook.

## Available files

- `predictions_raw.csv`: contains "**raw**" predictions derived using my model without implementing any strategy for fitting business constraints
- `predictions.csv`: contains **final** predictions derived using my model including a strategy for reflecting business constraints. More details are available in the notebook.
- `PerPay-task-MDG.ipynb`: Jupyter notebook with the proposed solution for the task
- `submission-validation.ipynb`: Jupyter notebook with the code for validating predictions