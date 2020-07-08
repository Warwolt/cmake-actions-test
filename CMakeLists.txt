project(CMakeActions)
cmake_minimum_required(VERSION 3.17.0)
enable_language(CXX)

set(SRC
    src/main.cpp
)

add_executable(hello_world
    ${SRC}
)
