.. AstroSubtractor documentation master file, created by
   sphinx-quickstart on Thu Mar 24 11:15:14 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to AstroSubtractor's documentation!
===============================
AstroSubtractor is an open-source program designed to perform background subtraction on astronomical images using an autoencoder-based Convolutional Neural Network (CNN). Leveraging the power of deep learning, AstroSubtractor employs an encoder-decoder architecture to learn and remove the background from astronomical images. By training on a dataset of paired images with and without background subtraction, AstroSubtractor learns to reconstruct the input image with the background removed, allowing for the efficient extraction and analysis of targeted celestial objects without the interference of the background.


Installation
==================
The current UNSTABLE version can be installed via pip:

.. code-block:: bash

    pip install AstroSubtractor


Pages
==================
.. toctree::
   :maxdepth: 1

   source/Page_1
   source/Page_2

Documentation
==================
Here is the documentation for all the modules:

.. toctree::
   :maxdepth: 1

   source/AstroSubtractor
