cmake_minimum_required(VERSION 4.3)
project(CPP_DSA)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

if (CMAKE_CXX_COMPILER_ID MATCHES "GNU|Clang")
    add_compile_options(
            -Wall
            -Wextra
            -Wpedantic
    )
endif()

add_executable(CPP_DSA main.cpp)
