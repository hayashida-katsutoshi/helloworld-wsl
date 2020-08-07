cmake_minimum_required(VERSION 3.6)
project(main CXX)

set(EXECUTABLE_OUTPUT_PATH build)
set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -O0")

add_executable(main src/main.cpp)
