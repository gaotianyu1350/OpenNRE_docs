Install
=========

Install as A Python Package
--------------------------------

We are now working on deploy OpenNRE as a Python package. Coming soon!

Using Git Repository
----------------------------

Clone the repository from our github page (don't forget to star us!)

::

    git clone https://github.com/thunlp/OpenNRE.git

Then install all the requirements:

::

    pip install -r requirements.txt

Note that we have excluded all data and pretrain files for the fast deployment. You can manually download them by running scripts in the ``benchmark`` and ``pretrain`` folders. For example, if you want to download FewRel dataset, you can run

::

    bash benchmark/download_fewrel.sh

.. NOTE:: When running our example codes or using a specific pretrain model, the toolkit will automatically download the files it needs.
