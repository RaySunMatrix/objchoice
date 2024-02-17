cmake_minimum_required(VERSION 3.28)
project(objchoice)

set(CMAKE_CXX_STANDARD 17)

add_executable(objchoice main.cpp
        develop/tools/task.cpp
        develop/tools/task.h)
