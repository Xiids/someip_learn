# CMake 最低版本要求
cmake_minimum_required(VERSION 3.10)

# 项目名称和版本号
project(MyProject VERSION 1.0)

# 指定 C++ 标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 将可执行文件添加到项目中
add_executable(MyProject main.cpp)
