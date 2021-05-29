cmake_minimum_required(VERSION 3.17)
project(panther_master)

set(CMAKE_CXX_STANDARD 17)


add_executable(project coorddesc/CoordDescMethod.h coorddesc/CoordDescMethod_test.cpp coorddesc/parallCoordDescMethod.h coorddesc/OldparallCoordDescMethod.h)
include_directories(.)
add_subdirectory(Google_tests)