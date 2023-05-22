=================
Neutrosopy Module
=================

.. automodule:: neutrosopy
   :members:
   :undoc-members:
   :show-inheritance:

Introduction
------------

The ``neutrosopy`` module provides functionality for working with neutrosophic numbers. Neutrosophic numbers are special numbers that have both a deterministic and an indeterministic part.

The module includes the following classes and functions:

Classes
~~~~~~~

NeutrosophicNumber
   Represents a neutrosophic number with a deterministic part (``a``) and an indeterministic part (``b``). Supports various mathematical operations such as addition, subtraction, multiplication, division, exponentiation, and more.

Functions
~~~~~~~~~

neutrolize_vector(X, deter=True)
   Constructs a neutrosophic vector from a 1-dimensional array, with the option to specify whether to assign the values to the deterministic or indeterministic part.

nexp(x, order=10)
   Approximates the neutrosophic exponential function using its Maclaurin series.

nsin(x, order=10)
   Approximates the neutrosophic sine function using its Maclaurin series.

nln(x, order=10)
   Approximates the neutrosophic natural logarithm function using a series based on the area hyperbolic tangent function.

Usage
-----

To use the module, import it as follows:

.. code-block:: python

   import neutrosopy

Examples
--------

Here are some examples demonstrating the usage of the module:

Construct a neutrosophic number:

.. code-block:: python

   n = neutrosopy.NeutrosophicNumber(2, 1)

Perform arithmetic operations on neutrosophic numbers:

.. code-block:: python

   a = neutrosopy.NeutrosophicNumber(3, 2)
   b = neutrosopy.NeutrosophicNumber(1, 4)
   c = a + b
   d = a * b

Construct a neutrosophic vector:

.. code-block:: python

   import numpy as np

   x = np.array([1, 2, 3, 4, 5])
   neutrosophic_vector = neutrosopy.neutrolize_vector(x)

Approximate the neutrosophic exponential function:

.. code-block:: python

   result = neutrosopy.nexp(2)

Approximate the neutrosophic sine function:

.. code-block:: python

   result = neutrosopy.nsin(1.5)

Approximate the neutrosophic natural logarithm function:

.. code-block:: python

