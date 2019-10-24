cmake_minimum_required(VERSION 3.15)
project(Playground)

set(CMAKE_CXX_STANDARD 14)

add_executable(Playground main.cpp CUDAtest/cudatest.cpp CUDAtest/add.cpp)