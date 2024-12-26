cmake_minimum_required(VERSION 3.10)
project(tdlib_backend)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(tdlib_backend
    tdlib_wrapper.h
    tdlib_wrapper.cpp
    main.cpp
)
