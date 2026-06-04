******************************
Playing Along With These Notes
******************************

These notes are a collection of Jupyter notebooks.  You can download
them and work through them on your own laptop or run them in the cloud
(e.g., with Google Colab):

Working on your own computer
============================

Clicking on the :octicon:`download` icon in the upper right let's you
download the raw notebook so you can run it on your local computer.

You'll need to install `pynucastro <https://pynucastro.github.io>`_ and `mesa_reader <https://github.com/wmwolf/py_mesa_reader>`_.
This can be done via pip as:

.. code:: bash

   pip install pynucastro mesa_reader

Using Google Colab
==================

Clicking on the :octicon:`rocket` icon in the upper right (on pages that are notebooks) will allow
launch the notebook directly in the cloud.

As with the local install, you'll need pynucastro and mesa_reader.  These
can be installed from within Colab by executing

.. code:: bash

   !pip install pynucastro mesa_reader

(note the ``!``) in a cell.

Some of the notebooks need data files.  These can be uploaded by selecting the
:octicon:`file-directory` icon on the vertical menu bar on the left:

.. image:: colab.png
   :align: center
   :width: 80%
