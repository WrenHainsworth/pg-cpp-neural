cmake_minimum_required(VERSION 3.21)
project(pg_neural)

set(CMAKE_CXX_STANDARD 14)

add_executable(pg_neural main.cpp MLP.cpp MLP.h)
