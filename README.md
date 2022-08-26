## Installation
It is expected to be used in a virtual environment, keeping all packages contained. To do so, clone the repository and run from a terminal:

`python3 -m venv ./venv`

If you change the path to the virtual environment (here expected to be *venv* inside the repository root), you must also replace the path used inside the notebooks (first code cell). More info on virtual environments [here](https://docs.python.org/3/library/venv.html).

Activate the virtual environment using `source venv/bin/activate`. Once inside the virtual environment, install the required packages using:

`pip install -r python-requirements`

## Running scripts
The scripts were implemented on [jupyter notebooks](https://jupyter.org). Run the jupyter server at the repository folder using `jupyter-notebook` inside the virtual environment.
