Welcome to Lumache's documentation!
===================================

**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
Lumache
=======

Lumache is a fictional Python library that serves as an excellent example for demonstrating Python packaging and documentation techniques. The name "Lumache" is derived from the Italian word for snails, reflecting the library's purpose of providing a "slow and steady" approach to solving common programming problems.

Features
--------

- **Easy-to-use API:** Lumache offers a simple and intuitive interface for both beginners and experienced developers.
- **Modular Design:** The library is designed to be flexible, allowing developers to include only the components they need.
- **Extensible:** Users can easily extend Lumache's functionality through plugins.

Installation
------------

You can install Lumache using pip:

.. code-block:: bash

   pip install lumache

Usage
-----

Here's a basic example of how to use Lumache in your project:

.. code-block:: python

   import lumache

   result = lumache.generate_slug("Hello World")
   print(result)

This code snippet will output a URL-friendly slug version of the input string.

License
-------

Lumache is licensed under the MIT License.
