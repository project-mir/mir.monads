Release notes
=============

This project uses `semantic versioning <http://semver.org/>`_.

1.0.1
-----

Changed
^^^^^^^

- Moved to Python 3.6

Fixed
^^^^^

- Data constructors no longer have a ``__dict__``.

1.0.0 (2016-11-23)
------------------

Removed
^^^^^^^

- Removed kleisli operator.
- Removed function currying.
- Removed function composition.

0.3.0 (2016-10-08)
------------------

Fixed
^^^^^

- ``Just.fmap()`` doesn't return Nothing appropriately.

0.2.0 (2016-09-25)
------------------

Added
^^^^^

- Identity monad.

0.1.0 (2016-09-25)
------------------

Initial release.
