# COMP0189 2025 lab exercises
This repo contains the lab exercises for the 2025 COMP0189 module. The exercises are mostly written as Python notebooks. We'll add each week's notebook before the lab session; afterwards, we'll also add a suggested solution.

## Setting up your environment
You can work on the lab exercises in 2 ways: either using a cloud-based editor called Google Colab, or locally on your machine.

### Cloud setup (Google Colab)
Using Colab doesn't require installing anything on your computer. Simply go to the [Google Colab](https://colab.research.google.com/) website and open the notebook you want to work on.

Note that Colab can be slow at times and has been known to crash. Make sure you save your work regularly.

### Local setup
You may prefer to work on the labs on your own computer. The code will often run faster than on Colab, especially since we don't need a GPU for the labs.

1. Download and install [Python](https://www.python.org/downloads/) for your operating system. If you're on Linux, the easiest way to do this is through your package manager rather than the Python website
2. Download and install [Git](https://git-scm.com/). Again, on Linux you should use your package manager for this
3. Open a terminal window and go to your home directory: `cd ~/`
4. Clone this repo: `git clone https://github.com/mouraomiranda/COMP0189-practical-2025`
5. Move into the repo: `cd COMP0189-practical-2025`
6. Create a virtual environment for this module: `python3 -m venv .venv`
    - This ensures that the packages required by the labs will not conflict with the ones required by other Python projects you may be working on
7. Activate the virtual environment: `source .venv/bin/activate`
8. Install Jupyter: `pip install jupyterlab`
9. You can now start the default Jupyter editor: `jupyter lab`
10. You may prefer to use [Visual Studio Code](https://code.visualstudio.com/) as your editor instead. If so:
    1. Install and open Visual Studio Code
    2. Install the Jupyter and Python extensions
    3. Open this repo: "File" -> "Open folder" -> (select the cloned repo on your computer)
    4. Open the notebook you want to work on. When asked to select a kernel, pick the virtual environment we created in `.venv` directory
