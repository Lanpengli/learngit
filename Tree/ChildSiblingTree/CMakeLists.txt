cmake_minimum_required(VERSION 3.13)

project(main)

include_directories("./*")

add_executable(main src/main.cpp src/child_sibling_tree.h src/test.cpp src/test.h)
