cmake_minimum_required(VERSION 3.17)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_FLAGS "-Wall -Wextra")
set(CMAKE_CXX_FLAGS_RELEASE "-O3")

project(dfvm_funcs)

set(SOURCE_CODE funcs.cpp)

add_library(${PROJECT_NAME} ${SOURCE_CODE})
