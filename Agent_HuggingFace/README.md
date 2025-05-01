Here's your updated `README.md` file with the step for installing **Jupyter** using `conda install jupyter` included under setup instructions:

---

# Agents HuggingFace Project

This project uses a Python environment managed by Anaconda and installs all required dependencies using a `requirements.txt` file.

## 🧰 Requirements

- Anaconda or Miniconda installed
- Python 3.10
- `requirements.txt` located in:  
  `C:\_BigDataCourses\_Projects\Agents_HuggingFace\requirements.txt`

## 🏁 Setup Instructions

Follow the steps below to set up the project environment.

### 1. Open Anaconda Prompt

### 2. Create a New Conda Environment

```bash
conda create --name agent_env python=3.10
```

### 3. Activate the Environment

```bash
conda activate agent_env
```

### 4. Install Jupyter Notebook

```bash
conda install jupyter
```

### 5. Install Required Python Packages

Make sure the `requirements.txt` file is located at:
```
C:\_BigDataCourses\_Projects\Agents_HuggingFace\requirements.txt
```

Then run:

```bash
pip install -r "C:\_BigDataCourses\_Projects\Agents_HuggingFace\requirements.txt"
```

> This will install libraries such as:
> - `pandas==2.2.3`
> - `numpy==2.2.3`
> - `ipywidgets==8.1.5`
> - `plotly==6.0.1`
> - `smolagents==1.13.0`
> - `openai==1.66.3`
> - And many more...

## 📁 Project Directory Structure

```
_BigDataCourses/
└── _Projects/
    └── Agents_HuggingFace/
        ├── requirements.txt
        ├── your_notebooks_or_scripts.ipynb
        └── README.md
```

## 🧹 Deactivating the Environment

To exit the conda environment when you're done:

```bash
conda deactivate
```

## 📌 Notes

- All packages will be installed via `pip`, even though you're using `conda`.
- `Jupyter` is installed via `conda` for better compatibility and performance.
- If you run into issues with conflicting dependencies, consider creating a `conda` environment file (`.yml`) instead.

---

Happy coding! 🚀
```

---
