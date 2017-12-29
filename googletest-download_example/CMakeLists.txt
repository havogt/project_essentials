cmake_minimum_required(VERSION 2.8.2)

project(googletest-download_example CXX)

include( ../googletest-download/googletest-download.cmake)

add_executable(example example.cc)
target_link_libraries(example gtest gtest_main)

