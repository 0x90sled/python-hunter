
Changelog
=========

0.2.0 (2015-03-26)
-----------------------------------------

* Added color support (and ``colorama`` as dependency).
* Added support for expressions in :class:`VarsPrinter`.
* Breaking changes:

  * Renamed ``F`` to :obj:`Q`. And :obj:`Q` is just a sugar function for :class:`Query`.
  * Renamed the ``PYTHON_HUNTER`` env variable to ``PYTHONHUNTER``.
  * Changed :class:`When` to take positional arguments.
  * Changed output to show 2 path components (still not configurable).
  * Changed :class:`VarsPrinter` to take positional arguments for the names.
* Improved error reporting for env variable activation (``PYTHONHUNTER``).


0.1.0 (2015-03-22)
-----------------------------------------

* First release on PyPI.
