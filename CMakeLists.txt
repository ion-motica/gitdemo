cmake_minimum_required(VERSION 3.23)
project(gitdemo)

set(CMAKE_CXX_STANDARD 14)

add_executable(gitdemo main.cpp cmake-build-debug/class2.cpp cmake-build-debug/class2.h "file 2.cpp")
