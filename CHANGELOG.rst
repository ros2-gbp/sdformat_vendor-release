^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sdformat_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.2 (2024-03-29)
------------------
* Update version, disable pybind11
  This also removes `BUILD_DOCS` since it's not a valid CMake argument in
  libsdformat.
* Require calling find_package on the underlying package
* Fix linter (`#1 <https://github.com/gazebo-release/sdformat_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese
