Changes
=======

Unreleased
----------

Interface changes
~~~~~~~~~~~~~~~~~
* On startup, files are now uploaded in order of mtime instead of in
  alphabetical order.  This cannot be precise, so the actual order
  should be considered arbitrary (a change from version 0.1.1), but it
  is still the most intuitive behaviour.

0.1.1 (2019-04-21)
------------------

Interface changes
~~~~~~~~~~~~~~~~~
* On startup, files are now uploaded in alphabetical order instead of in
  arbitrary (filesystem) order.  This is helpful if the files are
  timestamped in some way and does not hurt otherwise.

0.1.0 (2019-04-21)
------------------

* Initial release.
