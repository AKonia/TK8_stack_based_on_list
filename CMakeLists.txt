cmake_minimum_required(VERSION 2.8)
project(stack_based_on_list)


set(CMAKE_CURRENT_BINARY_DIR /bin)
set(CMAKE_LIBRARY_PATH /lib)
set(LIST_INCLUDE "${CMAKE_CURRENT_SOURCE_DIR}/include")
set(LIST_BINARIES "${CMAKE_CURRENT_SOURCE_DIR}/bin")
set(LIST_LIBRARIES "${CMAKE_CURRENT_SOURCE_DIR}/lib")

include_directories("${LIST_INCLUDE}" ./gtest)

add_subdirectory(samples)
add_subdirectory(lib)
add_subdirectory(tests)
