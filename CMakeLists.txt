cmake_minimum_required(VERSION 3.8)
project(Calendar)

set(CMAKE_CXX_STANDARD 11)

add_executable(calend body.cpp main.cpp)
add_executable(tests body.cpp tests.cpp)