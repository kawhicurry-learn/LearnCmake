# cmake 最低版本需求
cmake_minimum_required(VERSION 3.10)

# 工程名称
project(cmake_study)

# 设置
set(CMAKE_CXX_STANDARD 11)

# 编译源码生成目标
add_executable(cmake_study src/main.cc)