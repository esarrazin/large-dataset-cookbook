Large dataset cookbook
======================

The goal of this cookbook is to give you some examples to how handle large datasets.

Table of Contents
=================

* [Pandas](cookbook/pandas.ipynb)
* [Pandas and Pyarrow](cookbook/pyarrow.ipynb)
* [Pandas and file formats](cookbook/benchmark.ipynb)

How to use this cookbook
========================

To run the notebooks, you'll need Jupyter notebook and pandas on your computer.

To install locally, you can get these using `pip` (you may want to do this inside a virtual environment to avoid conflicting with your other libraries).

```bash
git clone https://github.com/esarrazin/large-dataset-cookbook.git
cd large-dataset-cookbook
python -m venv env_cookbook
source env_cookbook/bin/activate
pip install -r requirements.txt
jupyter-lab
```

A tab should open up in your browser at `http://localhost:8888`

License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

