cmake_minimum_required(VERSION 3.8)

project(practice)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)

include(cppcheck.cmake)
include(clang-format.cmake)

add_executable(practice ${SOURCE_FILES})