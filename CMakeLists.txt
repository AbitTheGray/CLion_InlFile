cmake_minimum_required(VERSION 3.28)
project(InlFile)

set(CMAKE_CXX_STANDARD 20)

add_library(InlFile STATIC test.hpp test.cpp)
