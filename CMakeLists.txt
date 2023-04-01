cmake_minimum_required(VERSION 3.8)
project("Math" LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(MathLibrary)
add_subdirectory(MathClient)