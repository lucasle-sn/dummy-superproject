cmake_minimum_required(VERSION 3.5.0)
project(dummy_superproject)

set(CMAKE_C_STANDARD                11)
set(CMAKE_C_STANDARD_REQUIRED       ON)
set(CMAKE_C_EXTENSIONS              ON)
set(CMAKE_CXX_STANDARD              14)
set(CMAKE_CXX_STANDARD_REQUIRED     ON)
set(CMAKE_CXX_EXTENSIONS            ON)

# Add third-party libraries
add_subdirectory(ext/dummy_lib)

add_subdirectory(executable)