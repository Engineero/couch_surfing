# Siamese neural network demonstration

Jupyter notebook for couch surfing presentation on Siamese neural networks.

To run, you will need to install Jupyter, TensorFlow, and some other
requirements listed in `requirements.txt`. If you're on Windows, I suggest
installing [Anaconda][1] first, then open the Anaconda Prompt from the Start
menu and create a virtual environment.

    $ conda create -n py36 python=3.6

This will create an environment called `py36` with Python 3.6. Next activate
the environment.

    $ conda activate py36

Finally, clone this repository, change directory to it, install the
requirements to run the notebook and run Jupyter.

    (py36) $ git clone git@github.com:Engineero/couch_surfing.git
    (py36) $ cd couch_surfing/
    (py36) $ pip install -r requirements.txt
    (py36) $ jupyter notebook

This will open a web browser with a file explorer. From the browser, you can
select the Jupyter notebook in this folder to open it and run. See Jupyter's
help documentation for tips on navigating and running notebooks.

[1]: https://www.anaconda.com/products/individual
