cmake_minimum_required(VERSION 3.28)
project(KmeansSequential C)

set(CMAKE_C_STANDARD 11)

add_executable(KmeansSequential main.c)
target_link_libraries(KmeansSequential m)
