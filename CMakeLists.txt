cmake_minimum_required(VERSION 3.13)
project(TransposeList)

set(CMAKE_CXX_STANDARD 14)

add_executable(TransposeList main.cpp dlist.h dlist.cpp.h transposelist.cpp.h transposelist.h)