cmake_minimum_required(VERSION 3.20)
project(template)

set(CMAKE_CXX_STANDART 14)

file(GLOB SOURCE_FILES src/*.cpp)

add_executable(template ${SOURCE_FILES})
