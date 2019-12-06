LwMEM documentation!
====================

.. image:: static/images/logo.svg
	:align: center

.. class::center

:ref:`download_library` · `Github <https://github.com/MaJerle/lwmem>`_

Features
^^^^^^^^

- Written in ANSI C99, compatible with ``size_t`` for size data types
- Platform independent, no architecture specific code
- FIFO (First In First Out) buffer implementation
- No dynamic memory allocation, data is static array
- Uses optimized memory copy instead of loops to read/write data from/to memory
- Thread safe when used as pipe with single write and single read entries
- Interrupt safe when used as pipe with single write and single read entries
- Suitable for DMA transfers from and to memory with zero-copy overhead between buffer and application memory
- Supports data peek, skip for read and advance for write
- User friendly MIT license

Requirements
^^^^^^^^^^^^

- C compiler
- Less than ``2kB`` of memory

Contribute
^^^^^^^^^^

We always welcome new contributors. To be as efficient as possible, we recommend:

#. Fork Github repository
#. Respect `C style & coding rules <https://github.com/MaJerle/c-code-style>`_ used by the library
#. Make a pull request to ``develop`` branch with new features or bug fixes

Alternatively you may:

#. Report a bug
#. Ask for a feature request

License
^^^^^^^

.. literalinclude:: license.txt

Table of contents
^^^^^^^^^^^^^^^^^

.. toctree::
    :maxdepth: 2

    get-started/index
    user-manual/index
    api-reference/index
