# Covid_Prediction_Model

## Project Setup Guide

This guide provides step-by-step instructions on how to set up a virtual environment for this project.

### Prerequisites

- **Python** installed (Python 3.6+ recommended)
- **Pip** (Python package installer)

### Step 1: Create a Virtual Environment

1. Open a terminal in the project directory.
2. Run the following command to create a virtual environment named `venv`:

    ```bash
    python -m venv venv
    ```

    This creates a new directory called `venv` in your project folder, which will contain all the dependencies for this project.

### Step 2: Activate the Virtual Environment

The activation command varies based on your operating system:

- **On Windows**:

    ```bash
    venv\\Scripts\\activate
    ```

- **On macOS/Linux**:

    ```bash
    source venv/bin/activate
    ```

Once activated, you should see the `(venv)` prefix in your terminal, indicating the virtual environment is active.

### Step 3: Install Project Dependencies

With the virtual environment activated, install any required dependencies using `pip`:

```bash
pip install -r requirements.txt
```
