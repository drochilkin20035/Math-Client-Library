cmake_minimum_required(VERSION 3.8)
project("MathLibrary" LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)

set(SOURCE_FILES "src/MathLibrary.cpp")
set(HEADER_FILES "src/MathLibrary.h")

add_library(MathLibrary STATIC ${HEADER_FILES} ${SOURCE_FILES})

target_include_directories(MathLibrary PUBLIC src)