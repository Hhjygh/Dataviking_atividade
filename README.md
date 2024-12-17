Aqui está a versão revisada com correções gramaticais e melhorias de estilo:

---

# Credit Scoring

- **Data Viking Class**  
- **By:**  
  - Rebeca Calmon  
  - Wesley Lima, PhD.  

## 1. Data Analysis

### 1.1 Environment Configurations

- **Poetry:** To manage our Python environment and required libraries.

Open a terminal window and run the following command to install Poetry:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

To confirm that Poetry is installed correctly, run:

```bash
poetry --version
```

- If the project contains files named `pyproject.toml` and `poetry.lock`, this means that a Poetry project has already been created. To install the project dependencies, run the following command:

```bash
poetry install
```

This command reads `pyproject.toml` and installs the specified dependencies along with their correct versions, ensuring consistency across different environments.

- If you don't have a `pyproject.toml` file, you can create a new project using the `poetry init` command.  
- To add a new Python library to your project, run:  
  ```bash
  poetry add pandas
  ```  
  *(Replace `pandas` with the name of the library you want to add.)*

- Poetry manages virtual environments for your projects. To activate the virtual environment, use:  
  ```bash
  poetry shell
  ```  

- You can also run a Python script without activating the virtual environment using:  
  ```bash
  poetry run python main.py
  ```

---

### 1.2 Python Notebook Configuration

- To create a **Jupyter Notebook** in VSCode:  
  1. Press `Ctrl + Shift + P` and select **"Create: New Jupyter Notebook"**.  
  2. In the top left, click on **"Select Kernel"**.  
  3. Under **Python Environments**, select the kernel named `dataviking_atividade`.

---