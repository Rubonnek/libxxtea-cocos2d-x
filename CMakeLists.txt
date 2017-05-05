cmake_minimum_required(VERSION 2.8)

set(LIBRARY_NAME xxtea)

project(${LIBRARY_NAME})
set(CMAKE_BUILD_TYPE Release)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)
add_library(${LIBRARY_NAME} SHARED src/xxtea.cpp)
