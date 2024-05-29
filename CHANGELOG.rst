^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sdformat_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2024-05-29)
------------------
* Update underlying version to 14.2.0
* Contributors: Addisu Z. Taddese

0.1.0 (2024-04-23)
------------------
* Use an alias target for root library
* Contributors: Addisu Z. Taddese

0.0.3 (2024-04-09)
------------------
* Add target with <pkg>::<pkg> format (`#2 <https://github.com/gazebo-release/sdformat_vendor/issues/2>`_)
  * gz-lib target aliases to gz-lib::gz-lib
  * Support the '::all' target
  ---------
* Fix issue with sourcing .dsv files
* Contributors: Addisu Z. Taddese

0.0.2 (2024-03-29)
------------------
* Update version, disable pybind11
  This also removes `BUILD_DOCS` since it's not a valid CMake argument in
  libsdformat.
* Require calling find_package on the underlying package
* Fix linter (`#1 <https://github.com/gazebo-release/sdformat_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese
