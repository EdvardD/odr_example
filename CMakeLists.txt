cmake_minimum_required(VERSION 2.8.4)
project(odr_example)

file(GLOB SOURCES "*.cpp")
add_executable(odr_example ${SOURCES})
