Simple online editor for landslide rst-based presentations.

Getting setup
-------------

Requirements for rsted:

* Flask
* Redis
* rst2html (from Docutils)

These requirements are expressed in the pip-requirements.txt file and may be
installed by running the following (from within a virtual environment)::

    pip install -r pip-requirements.txt


How to run
----------

From within your environment, just run::

    ./application.py

This will start a server on port 5000.  Just visit http://localhost:5000/ in
your browser.
