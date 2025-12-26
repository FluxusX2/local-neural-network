cmake_minimum_required(VERSION 4.1)
project(local_neuronal_engine)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_executable(local_neuronal_engine
        src/main.cpp)
