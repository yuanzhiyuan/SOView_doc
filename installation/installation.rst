.. pysodb_tutorial documentation master file, created by
   sphinx-quickstart on Thu Sep 29 16:15:04 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation
===========================================

1. Create a conda environment and activate it.

.. code-block:: python
   
   conda create --name SOView python=3.9 -y
   conda activate SOView

2. Clone the source code.

.. code-block:: python
   
   git clone https://github.com/yuanzhiyuan/SOView


3. Install SOView as a dependency or third-party package with pip:

.. code-block:: python
   
   cd SOView
   pip install .
   
4. Also install pysodb to load the data: https://pysodb.readthedocs.io/en/latest/