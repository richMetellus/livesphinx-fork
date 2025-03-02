Simple online editor for Sphinx on Flask.
####################################################

Try the reStructuredText version here: https://rsted.info.ucl.ac.be/

Intro 
******

This is a simple web application that allows you to write and preview
Sphinx-flavored reStructuredText documents.  It is built on Flask.

The fork version of this work simply make it possible to run the application 
in a virtual environment using pipenv and using python 3. 

Getting setup
**************

Requirements for rsted:

* Flask
* Redis
* rst2html (from Docutils)

These requirements are expressed in the ``Pipefile`` and the dependencies are 
in the ``Pipfile.lock``and may be
installed by running the following commands::


1. Install the pipenv package::

    pip install pipenv

2. Install the dependencies from the Pipfile.lock::

    pipenv install

3. Once all the installation is done you can activate the virtual environment::

    pipenv shell 


How to run
***********

From within your [virtual] environment, just run::

    python3 application.py

or simply::

    ./application.py

This will start a server on port 5000.  Just visit http://localhost:5000/ in
your browser.
