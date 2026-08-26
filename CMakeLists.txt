cmake_minimum_required(VERSION 4.3.2)

project(my_project)

add_executable(my_exe main.cpp)

target_include_directories(my_exe PUBLIC include)