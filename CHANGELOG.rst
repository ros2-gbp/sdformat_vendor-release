^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sdformat_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.9 (2025-02-07)
------------------
* Bump version to 14.7.0 (`#11 <https://github.com/gazebo-release/sdformat_vendor/issues/11>`_)
* Contributors: Addisu Z. Taddese

0.0.8 (2024-11-26)
------------------
* Bump version to 14.6.0 (`#10 <https://github.com/gazebo-release/sdformat_vendor/issues/10>`_)
* Contributors: Nate Koenig

0.0.7 (2024-11-05)
------------------
* Replace liburdfdom-dev with the ROS package urdfdom (`#6 <https://github.com/gazebo-release/sdformat_vendor/issues/6>`_)
  This ensures that we use the same version on all supported platforms
* Contributors: Addisu Z. Taddese

0.0.6 (2024-08-08)
------------------
* Update vendored package version to 14.5.0
* Contributors: Addisu Z. Taddese

0.0.5 (2024-07-15)
------------------
* Update vendored package version to 14.4.0
* Contributors: Addisu Z. Taddese

0.0.4 (2024-04-25)
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
