# WIP

1. [Installation](#installation-instructions)
2. [Usage](#usage)

## Installation instructions

In order to use our package and run your own experiments, we advise you to set up a virtual environment.

You will need Python 3.12. Then, create your virtual environment and switch to it:

```bash
python3.12 -m venv venv  # Linux
source venv/bin/activate  # Linux

py -3.12 -m venv venv  # Windows
.\venv\Scripts\Activate.ps1  # Windows
```

In order to use the notebooks, first create a kernel:

```bash
pip install ipykernel
ipython kernel install --user --name=notebooks
```

NB : If you ever need to remove an existing kernel, use the following lines

```bash
jupyter kernelspec list 
jupyter kernelspec uninstall <kernel-to-remove>
```

Finally, install all the requirements:

```bash
pip install -r requirements.txt  # Linux
pip install -r .\requirements.txt  # Windows
```

## Usage

All code is directly available in the notebook. Once you have followed the installations instructions you can start a jupyter server:

```bash
jupyter notebook
```

Select a notebook and check that are using the kernel you created during installation.

In order to use the notebooks, you can refer to any existing [cheatsheet](https://mljar.com/blog/jupyter-notebook-shortcuts-cheatsheet/) out there.
