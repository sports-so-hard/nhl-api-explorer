# NHL API Explorer

This project provides a Jupyter environment for exploring the NHL API using Python.

The API documenation can be found here: https://pypi.org/project/nhl-api-py/

**Repository:** `git@github.com:sports-so-hard/nhl-api-explorer.git`

## Prerequisites

Before you begin, you need to have Miniconda installed on your system. If you don't have it, please follow the official installation instructions for your operating system:

- [**Windows Installation Instructions**](https://www.google.com/search?q=https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html%23windows)
- [**macOS Installation Instructions**](https://www.google.com/search?q=https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html%23macos)
- [**Linux Installation Instructions**](https://www.google.com/search?q=https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html%23linux)

## Environment Setup

Follow these steps to create the project's Conda environment from the `environment.yml` file.

### 1. Clone the Repository (Optional)

If you haven't already, clone the project repository and navigate into the directory:

```
git clone git@github.com:sports-so-hard/nhl-api-explorer.git
cd nhl-api-explorer
```

### 2. Create the Conda Environment

Open your terminal (Anaconda Prompt on Windows, Terminal on macOS/Linux) in the project directory and run the following command. This will create a new environment named `nhl-api-explorer` with all the necessary packages.

```
conda env create -f environment.yml
```

Conda will solve the dependencies and download all the required packages. This might take a few minutes.

### 3. Activate the Environment

Once the creation is complete, activate your new environment:

```
conda activate nhl-api-explorer
```

Your terminal prompt should now be prefixed with `(nhl-api-explorer)`.

## Usage

With the environment active, you can start a Jupyter session to begin working with your notebooks.

**To start Jupyter Notebook:**

```
jupyter notebook
```

**Or, to start JupyterLab:**

```
jupyter lab
```

This will open a new tab in your web browser, ready for you to create or open notebooks.

## Cleaning Up the Repository

When you are finished with the project and want to remove the Conda environment and its packages, follow these steps.

### 1. Deactivate the Environment

If the `nhl-api-explorer` environment is still active, deactivate it:

```
conda deactivate
```

### 2. Remove the Environment

Now, you can safely remove the environment. This will delete all packages installed within it.

```
conda env remove --name nhl-api-explorer
```

Confirm that you want to proceed if prompted.