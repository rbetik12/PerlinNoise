cmake_minimum_required(VERSION 3.17)
project(PerlinNoise)

set(CMAKE_CXX_STANDARD 17)

add_library(PerlinNoise PerlinNoise.hpp PerlinNoise.cpp)