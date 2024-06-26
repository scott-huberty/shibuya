:description: Sphinx copybutton works well with Shibuya Sphinx theme.

.. _sphinx-copybutton:

sphinx-copybutton
=================

Add a little “copy” button to the right of your code blocks. This extension
is maintained by Executable Books.

- **Documentation**: https://sphinx-copybutton.readthedocs.io/
- **Source Code**: https://github.com/executablebooks/sphinx-copybutton

Install
-------

.. code-block:: bash

    pip install sphinx-copybutton

Then, add the extension to your ``conf.py``:

.. code-block:: python
    :caption: conf.py

    extensions = [
        # ...
        "sphinx_copybutton",
    ]

.. hint::

    Hovering on the code block above, you will see a copy button.
