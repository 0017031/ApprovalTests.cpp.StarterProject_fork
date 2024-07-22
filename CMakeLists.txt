cmake_minimum_required(VERSION 3.20)
project(ApprovalTests.cpp.StarterProject)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_VERBOSE_MAKEFILE on)

enable_testing()
add_subdirectory(code) # my_code, e.g. my-lib

add_subdirectory(lib/ApprovalTests)  				# approval_test.hpp                       
add_subdirectory(lib/catch2_v3_src)        			# catch2_v3, submodule
add_subdirectory(lib/catch2_v3_amalgamated)			# catch2_v3_amalgamated, sub-dir

add_subdirectory(approval-tests_with_catch2v3)
add_subdirectory(approval-tests_with_catch2v3_amalgamated)

