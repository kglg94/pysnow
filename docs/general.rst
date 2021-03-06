Compatibility
-------------

Python 2.6+ and Python 3.3+


Installing
----------

.. code-block:: bash

    $ pip install pysnow


Testing
-------

The code is automatically tested using **travis** and **nose**.

To run tests manually, move to the cloned directory and run::

    $ nosetests --cover-package=pysnow --with-coverage --cover-erase



Demo!
-----
This demo features the :class:`pysnow.QueryBuilder` and shows an example of how to fetch records using the **incident** table API.

.. image:: pysnow.gif

License
-------

MIT License

Copyright (c) 2017 Robert Wikman <rbw@vault13.org>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
