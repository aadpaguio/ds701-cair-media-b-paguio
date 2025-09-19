I use uv to manage my virtual environments. If you want to run the notebooks, clone it to your machine and just run `uv sync`. If you haven't used uv before, uv automatically builds the .venv using the uv.lock file. You just need uv installed on your machine. 

In case you don't want to use uv, I've added a requirements.txt file you can use. just create a conda environment or a standard virtual environment and run `pip install -r requirements.txt`

The notebook `scraping_test.ipynb` contains my scraping demo of the MassLive archives.
