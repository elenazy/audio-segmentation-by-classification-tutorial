# audio-segmentation-by-classification-tutorial

A jupyter notebook for a multiclass **audio segmentation** tutorial and demo.

You can read a static version of this notebook [here](http://nbviewer.jupyter.org/github/amsehili/audio-segmentation-by-classification-tutorial/blob/master/multiclass_audio_segmentation.ipynb#).

If you want to run the code on your machine:

- Install Pyaudio dependencies (if you want audio play back)

        (Ubuntu)$ sudo apt-get install python-pyaudio portaudio19-dev

# Recommended #

- Install [Anaconda](https://www.continuum.io/downloads)

- Clone this repository and run Jupyter:

        git clone https://github.com/amsehili/audio-segmentation-by-classification-tutorial.git
        cd audio-segmentation-by-classification-tutorial
        conda env create -f linux-64-environment.yml
        source activate audio
        jupyter notebook

# Old way #

- Install [Jupyter](https://jupyter.readthedocs.org/en/latest/install.html)

        pip install jupyter

- Install [auditok](https://github.com/amsehili/auditok)
 
        pip install auditok

- Install other requirements

  - [numpy](http://www.numpy.org/)
  - [scikit-learn](http://scikit-learn.org/stable/)
  - [matplotlib](http://matplotlib.org/)
  - [Pyaudio](http://people.csail.mit.edu/hubert/pyaudio/) (if you want audio play back)

- Clone this repository and run Jupyter:

        git clone https://github.com/amsehili/audio-segmentation-by-classification-tutorial.git
        cd audio-segmentation-by-classification-tutorial
        jupyter notebook
