cmake_minimum_required(VERSION 3.8)
project("MathClient" LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)

set(SOURCE_FILES "src/MathClient.cpp")
add_executable(MathClient ${SOURCE_FILES})

target_link_libraries(MathClient MathLibrary)
