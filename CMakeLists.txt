cmake_minimum_required(VERSION 3.6)

project(tegic CXX)

set(CMAKE_CXX_STANDARD 14)

enable_testing()

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/Executable)
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/Library)

add_subdirectory(Sources)
add_subdirectory(Tests)
