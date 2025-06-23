cmake_minimum_required(VERSION 3.10)

# 项目名称和版本
project(cmake_demo VERSION 1.0)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 添加源码文件夹
add_executable(cmake_demo src/main.cpp)
