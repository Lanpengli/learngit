cmake_minimum_required(VERSION 3.13)

project(main)

include_directories("./*")

add_executable(main src/main.cpp src/min_heap.cpp src/min_heap.h)
