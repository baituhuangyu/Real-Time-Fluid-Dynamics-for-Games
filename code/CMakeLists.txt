cmake_minimum_required(VERSION 3.16)
project(demo)

set(CMAKE_CXX_STANDARD 11)

add_executable(demo demo.c solver.c)
target_link_libraries(demo GL glut GLU)

