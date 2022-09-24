# Mini Project 1
Details found in PDF in this folder. Repo Link https://github.com/btakli/COMP472-Mini-Projects/

## Anaconda environment setup (Windows)
1. Download `miniconda` using this link https://conda.io/projects/conda/en/latest/user-guide/install/windows.html
2. once installed, open `Anaconda Prompt` on Windows and type `conda create --name comp472_mp1 python=3.8`. (On Mac you can use homebrew to install miniconda and type this command directly in terminal)
3. then type `conda activate comp472_mp1` to activate the environment on the console and `conda deactivate` to deactivate. 
4. To install all necessary requirements, activate your environment and type `conda install --file requirements.txt` from inside this directory.
5. To use jupyter notebook, there are 2 options:
    1. in your conda environment type `jupyter notebook` from in the directory containing the ipynb file. [More instructions found here](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).
    2. Download the VSCode Jupyter Notebook Extension and run it from within VSCODE (Preferred option)
6. In VSCode, to use this environment in Jupyter Notebook, simply select it from within Jupyter Notebook, you do not need to have it active.
