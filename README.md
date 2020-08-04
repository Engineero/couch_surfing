# couch_surfing

Jupyter notebook for couch surfing presentation on Siamese neural networks.

To run, you will need to install Jupyter, TensorFlow, and some other
requirements listed in `requirements.txt`. If you're on Windows, I suggest
installing [Anaconda][1] first, then open the Anaconda Prompt from the Start
menu and create a virtual environment with:

    $ conda create -n tf2 python=3.6

This will create an environment called `tf2` with Python 3.6. Next activate
the environment and install needed packages.

    $ conda activate tf2
    (tf2) $ pip install -r requirements.txt

Finally, navigate to this folder and run Jupyter:

   $ cd /path/to/this/folder
   $ jupyter notebook

This will open a web browser with a file explorer. From the browser, you can
select the Jupyter notebook in this folder to open it and run. See Jupyter's
help documentation for tips on navigating and running notebooks.

[1]: https://www.anaconda.com/products/individual
