How to set up everything for the course:

1. Download the Course Material from GitHub

2. Install Conda
   
   You must install Miniconda or Anaconda (Miniconda is lighter)
   
   https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html

3. Install the Course Environment
  
   Inside the folder you downloaded from GitHub, you will find the file `environment.yml`.

   Open a terminal and create the environment:

   `conda env create -f environment.yml`

   Then activate the enviromnet:

   `conda activate drug_discovery`

4. Install an editor:

   Visual Studio Code (VS Code) is recommended: https://code.visualstudio.com/

   Install the extensions: Python, Jupyter

   Otherwise, you can use JupyterLab (Web Interface): https://jupyter.org/install

5. Open the Course Folder in VS Code (or JupyterLab)

   Open VS Code (or any alternative)

   Click File → Open Folder

   Select the folder you downloaded from GitHub

   Open the notebook: 0_python_introduction.ipynb

   At the top right: Select the kernel → drug_discovery

6. Complete the 0_python_introduction.ipynb

   This will introduce you to Python basics
