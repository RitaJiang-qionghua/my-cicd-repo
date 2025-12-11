cmake_minimum_required(VERSION 3.10)
project(HelloCICD)

# 设置C++标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 添加可执行文件，源代码在 src/main.cpp
add_executable(hello_app src/main.cpp)