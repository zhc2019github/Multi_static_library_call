cmake_minimum_required(VERSION 3.17)
project(cliontest)
set(CMAKE_CXX_STANDARD 11)

link_directories(/Users/zhanghuaichao/cmake/Multi_static_library_call/separate/add)

add_executable(cliontest main.cpp)
target_link_libraries(cliontest  mathadd)
target_include_directories(cliontest PRIVATE add)
