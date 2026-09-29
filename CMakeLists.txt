cmake_minimum_required(VERSION 3.20)
project(todo_list VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

option(TODO_BUILD_APP "Build application" ON)

add_subdirectory(src)
