cmake_minimum_required(VERSION 3.10)
project(mimick_vendor)

find_package(ament_cmake REQUIRED)
find_package(ament_cmake_vendor_package REQUIRED)

ament_vendor(mimick_vendor
  VCS_URL https://github.com/ros2/Mimick.git
  VCS_VERSION 8d17528528167707ae38e1c6803a1e6a5845b01d
)

ament_export_dependencies(mimick)

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()

ament_package()
