cmake_minimum_required(VERSION 3.5)
project(test)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE SOURCES *.cc)

add_executable(${PROJECT_NAME} ${SOURCES})
