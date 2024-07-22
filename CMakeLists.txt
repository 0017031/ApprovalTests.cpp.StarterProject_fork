cmake_minimum_required(VERSION 3.20)
project(ApprovalTests.cpp.StarterProject)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_VERBOSE_MAKEFILE on)

enable_testing()
add_subdirectory(code)
add_subdirectory(lib)
add_subdirectory(lib/catch2_v3_src)
add_subdirectory(tests)


