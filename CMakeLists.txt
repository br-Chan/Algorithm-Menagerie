# CMakeList.txt : CMake project for Algorithm-Menagerie, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Algorithm-Menagerie")

# Add source to this project's executable.
add_executable (Algorithm-Menagerie "Algorithm-Menagerie.cpp" "Algorithm-Menagerie.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Algorithm-Menagerie PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
