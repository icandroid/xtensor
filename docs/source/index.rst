.. Copyright (c) 2016, Johan Mabille and Sylvain Corlay

   Distributed under the terms of the BSD 3-Clause License.

   The full license is in the file LICENSE, distributed with this software.

.. image:: http://quantstack.net/assets/images/xtensor.svg

Multi-dimensional arrays with broadcasting and lazy computing.

Introduction
------------

`xtensor` is a C++ library meant for numerical analysis with multi-dimensional array expressions.

`xtensor` provides

- an extensible expression system enabling **lazy broadcasting**.
- an API following the idioms of the **C++ standard library**.
- tools to manipulate array expressions and build upon `xtensor`.

Containers of `xtensor` are inspired by `NumPy`_, the Python array programming library. **Adaptors** for existing data structures to be plugged into our expression system can easily be written. In fact, `xtensor` can be used to **process numpy data structures inplace** using Python's `buffer protocol`_. For more details on the numpy bindings, check out the xtensor-python_ project.

`xtensor` requires a modern C++ compiler supporting C++14. The following C++ compilers are supported:

- On Windows platforms, Visual C++ 2015 Update 2, or more recent
- On Unix platforms, gcc 4.9 or a recent version of Clang

Licensing
---------

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

This software is licensed under the BSD-3-Clause license. See the LICENSE file for details.


.. toctree::
   :caption: INSTALLATION
   :maxdepth: 2

   installation

.. toctree::
   :caption: USAGE
   :maxdepth: 2

   basic_usage
   expression
   container
   operator
   view
   builder
   related

.. toctree::
   :caption: API REFERENCE
   :maxdepth: 2
   
   api/expression_index
   api/container_index
   api/function_index
   api/xmath

.. toctree::
   :caption: DEVELOPER ZONE

   compilers
   releasing

.. toctree::
   :caption: MISCELLANEOUS

   numpy
   numpy-differences
   closure-semantics

.. _NumPy: http://www.numpy.org
.. _Buffer Protocol: https://docs.python.org/3/c-api/buffer.html
.. _libdynd: http://libdynd.org
.. _xtensor-python: https://github.com/QuantStack/xtensor-python
