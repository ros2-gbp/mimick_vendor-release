cmake_minimum_required(VERSION 3.10)
project(mimick_vendor)

find_package(ament_cmake REQUIRED)
find_package(ament_cmake_vendor_package REQUIRED)

set(CMAKE_ARGS)
if(WIN32 AND "${CMAKE_SYSTEM_PROCESSOR}" MATCHES "^(x86_|x86-|AMD|amd|x)64$")
  list(APPEND CMAKE_ARGS -Ax64)
endif()

ament_vendor(mimick_vendor
  VCS_URL https://github.com/ros2/Mimick.git
  VCS_VERSION de11f8377eb95f932a03707b583bf3d4ce5bd3e7
  CMAKE_ARGS ${CMAKE_ARGS}
)

ament_export_dependencies(mimick)

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()

ament_package()
