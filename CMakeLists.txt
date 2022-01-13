cmake_minimum_required(VERSION 3.16)
project(hs C)

set(CMAKE_C_STANDARD 11)

add_executable(hs main.c test2.c)
add_executable(test2 test2.c)