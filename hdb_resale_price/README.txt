# Prerequisites

- You need to have Jupyter Labs installed. See install instructions [here](https://jupyter.org/install).

# How to run the file?

1. Create a new virtual env with the command `python -m venv env`.
2. Activate your virtual environment with the command `source env/bin/activate`.
3. Install the IPython kernel for Jupyter if you don't have it with the command `pip install ipykernel`.
4. Add your virtual environment to Jupyter with the command `python -m ipykernel install --user --name=env`.
5. Install the required packages to your env with `pip install -r requirements.txt`.
6. Run `jupyter notebook` and open hdb_resale_price.ipynb