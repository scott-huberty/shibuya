:description: A theme option enables the display of an announcement banner.

Announcement
============

.. rst-class:: lead

    Display an announcement banner at the top of the page.

----

When there's something to announce, you can include the announcement
content in the ``conf.py`` announcement option.

.. code-block:: python
    :caption: conf.py

    html_theme_options = {
      "announcement": "The content of the announcement",
    }

.. note::

    HTML is allowed in the ``announcement`` option.

Here shows an example with ``announcement`` configuration.

.. container:: image-1

    .. image:: /_static/screenshots/homepage-light.jpg
      :class: light-only
      :align: center

    .. image:: /_static/screenshots/homepage-dark.jpg
      :class: dark-only
      :align: center
