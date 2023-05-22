===================
Neutrosophic Module
===================

.. automodule:: neutrosophic
   :members:
   :undoc-members:
   :show-inheritance:

Introduction
------------

The ``neutrosophic`` module provides functionality for working with neutrosophic numbers. Neutrosophic numbers are special numbers that have both a deterministic and an indeterministic part.

Usage
-----
To use the module, simply import it as follows:

.. code-block:: python

   import neutrosophic

Examples
--------

Here are some examples demonstrating the usage of the module:

Construct a neutrosophic number:

.. code-block:: python

   n = neutrosophic.NeutrosophicNumber(2, 1)

Perform arithmetic operations on neutrosophic numbers:

.. code-block:: python

   a = neutrosophic.NeutrosophicNumber(3, 2)
   b = neutrosophic.NeutrosophicNumber(1, 4)
   c = a + b
   d = a * b

Construct a neutrosophic vector:

.. code-block:: python

   import numpy as np

   x = np.array([1, 2, 3, 4, 5])
   neutrosophic_vector = neutrosophic.neutrolize_vector(x)

Approximate the neutrosophic exponential function:

.. code-block:: python

   result = neutrosophic.nexp(2)

Approximate the neutrosophic sine function:

.. code-block:: python

   result = neutrosophic.nsin(1.5)

Approximate the neutrosophic natural logarithm function:

.. code-block:: python

   result = neutrosophic.nln(2.5)



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
