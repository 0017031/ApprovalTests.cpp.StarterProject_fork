 # if(NOT TARGET catch2_v3_amalgamated)
    set(LIB_NAME catch2_v3_amalgamated)
    add_library(${LIB_NAME}
		catch_amalgamated.cpp
		catch_amalgamated.hpp
	)
    target_include_directories(${LIB_NAME} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
# endif()

