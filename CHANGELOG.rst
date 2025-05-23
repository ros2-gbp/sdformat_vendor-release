^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sdformat_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.2.5 (2025-05-23)
------------------
* Bump version to 15.3.0 (`#14 <https://github.com/gazebo-release/sdformat_vendor/issues/14>`_)
* Contributors: Ian Chen, Jose Luis Rivero

0.2.4 (2025-02-19)
------------------
* Bump version to 15.2.0 (`#12 <https://github.com/gazebo-release/sdformat_vendor/issues/12>`_)
* Contributors: Carlos Agüero

0.2.3 (2024-11-26)
------------------
* Bump version to 15.1.1 (`#9 <https://github.com/gazebo-release/sdformat_vendor/issues/9>`_)
* Contributors: Michael Carroll

0.2.2 (2024-11-14)
------------------
* Bump version to 15.1.0 (`#8 <https://github.com/gazebo-release/sdformat_vendor/issues/8>`_)
* Contributors: Steve Peters

0.2.1 (2024-11-05)
------------------
* Replace liburdfdom-dev with the ROS package urdfdom (`#6 <https://github.com/gazebo-release/sdformat_vendor/issues/6>`_)
  This ensures that we use the same version on all supported platforms
* Contributors: Addisu Z. Taddese

0.2.0 (2024-09-30)
------------------
* Bump version to 15.0.0 (`#5 <https://github.com/gazebo-release/sdformat_vendor/issues/5>`_)
* Apply prerelease suffix (`#3 <https://github.com/gazebo-release/sdformat_vendor/issues/3>`_)
* Upgrade to Ionic
* Contributors: Addisu Z. Taddese

0.1.3 (2024-08-08)
------------------
* Update vendored package version to 14.5.0
* Contributors: Addisu Z. Taddese

0.1.2 (2024-07-15)
------------------
* Update vendored package version to 14.4.0
* Contributors: Addisu Z. Taddese

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
