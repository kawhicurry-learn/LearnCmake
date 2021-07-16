cmake_minimum_required(VERSION 3.10)

project(hello)

set(CMAKE_CXX_STANDARD 11)

aux_source_directory(src DIR_SRCS)

add_subdirectory(src/lib)

add_executable(thehello src/main.cpp)

target_link_libraries(thehello hello)