ipydocker
===============================

A Jupyter Widget for Docker

Installation
------------

To install use pip(`not work now!`): 

    $ pip install ipydocker
    $ jupyter nbextension enable --py --sys-prefix ipydocker


For a development installation (requires npm),

    $ git clone https://github.com/JMHOO/ipydocker.git
    $ cd ipydocker
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix ipydocker
    $ jupyter nbextension enable --py --sys-prefix ipydocker
