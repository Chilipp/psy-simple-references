============================================
Reference figures for the psy-simple package
============================================

This repository is mainly designed for the continuous integration
of the psy-simple package. If you cloned the psy-simple_ repository,
get the identifier via through the get_ref_dir.py_ file::

    python tests/get_ref_dir.py -b

and the right path via::

    python tests/get_ref_dir.py

and in the cloned ``psy-simple`` repository, run::

    git submodule update --init `python tests/get_ref_dir.py`

.. _psy-simple: https://github.com/Chilipp/psy-simple
.. _get_ref_dir.py: https://github.com/Chilipp/psy-simple/blob/master/tests/get_ref_dir.py
