^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mimick_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.8.0 (2024-06-17)
------------------
* Update to the commit that includes DT_GNU_HASH. (`#37 <https://github.com/ros2/mimick_vendor/issues/37>`_)
* Contributors: Chris Lalancette

0.7.0 (2024-04-26)
------------------

0.6.1 (2024-03-28)
------------------
* Bump vendored mimick version for `ros2/Mimick#32 <https://github.com/ros2/Mimick/issues/32>`_ (`#35 <https://github.com/ros2/mimick_vendor/issues/35>`_)
* Update to the commit that fixes mmk_noreturn. (`#34 <https://github.com/ros2/mimick_vendor/issues/34>`_)
* Contributors: Chris Lalancette, Michael Carroll

0.6.0 (2023-11-06)
------------------
* Update to the commit the fixes exe stack on macOS. (`#33 <https://github.com/ros2/mimick_vendor/issues/33>`_)
* Contributors: Chris Lalancette

0.5.0 (2023-08-21)
------------------
* Update to the comment that fixes the executable stack. (`#32 <https://github.com/ros2/mimick_vendor/issues/32>`_)
* Update to take advantage of TARGET_ARCH (`#28 <https://github.com/ros2/mimick_vendor/issues/28>`_)
* Contributors: Chris Lalancette, Michael Carroll

0.4.1 (2023-07-11)
------------------
* Switch to ament_cmake_vendor_package (`#31 <https://github.com/ros2/mimick_vendor/issues/31>`_)
* Contributors: Scott K Logan

0.4.0 (2023-04-27)
------------------

0.3.2 (2023-02-14)
------------------
* [rolling] Update maintainers - 2022-11-07 (`#29 <https://github.com/ros2/mimick_vendor/issues/29>`_)
* Contributors: Audrow Nash

0.3.1 (2022-09-13)
------------------
* Mirror rolling to master
* Contributors: Audrow Nash

0.3.0 (2022-04-29)
------------------

0.2.8 (2022-03-25)
------------------
* support pi zero (`#24 <https://github.com/ros2/mimick_vendor/issues/24>`_)
* Contributors: Brett Downing

0.2.7 (2022-01-14)
------------------
* Update maintainers to Geoffrey Biggs (`#23 <https://github.com/ros2/mimick_vendor/issues/23>`_)
* Update to latest commit for Apple M1 support (`#20 <https://github.com/ros2/mimick_vendor/issues/20>`_)
* Contributors: Audrow Nash, Christophe Bedard

0.2.6 (2021-03-18)
------------------
* Always preserve source permissions in vendor packages (`#19 <https://github.com/ros2/mimick_vendor/issues/19>`_)
* Contributors: Scott K Logan

0.2.5 (2021-02-01)
------------------
* Suppress update of pinned git repository (`#17 <https://github.com/ros2/mimick_vendor/issues/17>`_)
* Don't overwrite -Wno-dev CMake argument (`#18 <https://github.com/ros2/mimick_vendor/issues/18>`_)
* Contributors: Scott K Logan

0.2.4 (2021-01-25)
------------------
* Add missing build tool dependency on 'git' (`#16 <https://github.com/ros2/mimick_vendor/issues/16>`_)
* Update tag for armv7l support. (`#15 <https://github.com/ros2/mimick_vendor/issues/15>`_)
* Contributors: Michel Hidalgo, Scott K Logan

0.2.3 (2020-12-08)
------------------
* Update tag for new cmake version requirement (`#14 <https://github.com/ros2/mimick_vendor/issues/14>`_)
* Export include directories (`#13 <https://github.com/ros2/mimick_vendor/issues/13>`_)
* Update package maintainers (`#10 <https://github.com/ros2/mimick_vendor/issues/10>`_)
* Contributors: Michel Hidalgo, Stephen Brawner

0.2.2 (2020-09-18)
------------------
* Suppress cppcheck for MMK_MANGLE\_ (`#8 <https://github.com/ros2/mimick_vendor/issues/8>`_)
* Change Mimick tagged version. (`#7 <https://github.com/ros2/mimick_vendor/issues/7>`_)
* Contributors: Michel Hidalgo, brawner

0.2.1 (2020-08-05)
------------------
* Change tag to pull latest Mimick version (`#6 <https://github.com/ros2/mimick_vendor/issues/6>`_)
* Contributors: Jorge Perez

0.2.0 (2020-07-30)
------------------
* Pin Mimick version. (`#5 <https://github.com/ros2/mimick_vendor/issues/5>`_)
* Contributors: Michel Hidalgo

0.1.1 (2020-07-29)
------------------
* Change imported dep to match ROS 2 fork (`#4 <https://github.com/ros2/mimick_vendor/issues/4>`_)
* Contributors: Jorge Perez

0.1.0 (2020-07-28)
------------------
* Avoid CMAKE_BUILD_TYPE warnings on Windows. (`#3 <https://github.com/ros2/mimick_vendor/issues/3>`_)
* Remove dep tag + add maintainer(`#2 <https://github.com/ros2/mimick_vendor/issues/2>`_)
* Configure MSVC x64 builds when appropriate. (`#1 <https://github.com/ros2/mimick_vendor/issues/1>`_)
* First iteration vendor for Mimick library
* Contributors: Jorge Perez, Michel Hidalgo
