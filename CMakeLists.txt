cmake_minimum_required(VERSION 3.5 FATAL_ERROR)
project(text2cpp LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQURIED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
add_executable(bin2cpp src/bin2cpp.cpp)
install(TARGETS bin2cpp DESTINATION bin)

